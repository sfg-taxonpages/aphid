<template>
  <VCard>
    <VCardHeader>
      <h3>Image matrix</h3>
    </VCardHeader>
    <VCardContent>
      <VSpinner
        v-if="isLoading"
        logo-class="w-8 h-8"
        legend=""
      />
      <RouterLink
        v-if="otuIds.length"
        class="text-sm"
        :to="{
          name: 'image-matrices-id',
          params: {
            id: 0
          },
          query: {
            otu_filter: otuIds.join('|')
          }
        }"
      >
        Species of <span v-html="taxon.cached_html" />
      </RouterLink>
      <span
        class="text-sm"
        v-else
      >
        No descendants observations found
      </span>
    </VCardContent>
  </VCard>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import { makeAPIRequest } from '@/utils/request.js'

const props = defineProps({
  taxon: {
    type: Object,
    required: true
  }
})

const otuIds = ref([])
const isLoading = ref(false)

onMounted(async () => {
  isLoading.value = true

  try {
    const { data } = await makeAPIRequest.get('/observations', {
      params: {
        taxon_name_id: [props.taxon.id],
        observation_type: ['Observation::Media'],
        descendants: true,
        per: 2000
      }
    })

    const ids = data
      .filter((o) => o.observation_object_type === 'Otu')
      .map((o) => o.observation_object_id)

    otuIds.value = [...new Set(ids)]
  } catch {
  } finally {
    isLoading.value = false
  }
})
</script>
