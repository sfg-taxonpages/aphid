<div style='display: flex; justify-content: center; align-items: center;'>
# {{ app:project_name }}

<autocomplete-otu class="w-80 place-content-center" placeholder="Search by taxon name"/>

Search for your taxon of choice or start at [Aphidomorpha]({{app:project_url}}/otu/899787/overview), [Aphididae]({{app:project_url}}/otu/899953/overview), [Adelgidae]({{app:project_url}}/otu/899910/overview), or [Phylloxeridae]({{app:project_url}}/otu/899910/overview).

<table style='border: 0'>
<tr><td colspan="6" style="text-align: center">Valid Species: <ValidSpeciesCount/>; <ProjectStats :data="['Taxon names', 'Collection objects', 'Project sources', 'Documents', 'Citations', 'Images']" class="capitalize"/></td></tr>
</table>
</div>
