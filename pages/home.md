# {{ app:project_name }}

<autocomplete-otu class="w-80 place-content-center" placeholder="Search by taxon name"/>

Try searching for **_Acyrthosiphon pisum_**, **_Daktulosphaira vitifoliae_**, **_Adelges tsugae_**, or start at [Aphidomorpha]({{app:project_url}}/otu/899787/overview), [Aphididae]({{app:project_url}}/otu/899953/overview), [Adelgidae]({{app:project_url}}/otu/899910/overview), or [Phylloxeridae]({{app:project_url}}/otu/899910/overview).

<div style='display: flex; justify-content: center; align-items: center;'>
<table style='border: 0'>
<tr><td colspan="6" style="text-align: center">Valid Species: <ValidSpeciesCount/>; <ProjectStats :data="['Taxon names', 'Collection objects', 'Project sources', 'Documents', 'Citations', 'Images']" class="capitalize"/></td></tr>
</table>
</div>
