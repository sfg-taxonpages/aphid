---
# See project.yml for variables.
---

<script setup>
const { project_name } = __APP_ENV__
const { focal_taxon } = __APP_ENV__
const { focal_taxon_common_name } = __APP_ENV__
const { contact_email } = __APP_ENV__
</script>

# {{ project_name }}

## Mission statement

{Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.}
   			 
## Search

<autocomplete-otu class="w-80"/>

_Try searching for "{Aidae}", "{Aus}", "{Aus bus}"}, or start at [{Order}]({{project_url}}/otu/{id}/overview), [{Family}]({{project_url}}/otu/{id}/overview), or [{Genus}]({{project_url}}/otu/{id}/overview)._

## Discover more

Our [About](about) page contains an [overview](about#overview) of the content and its [gaps](about#gaps-as-opportunity) and [history](about#history), the [team](about#team) and [support](about#support) behind the **{{project_name}}** and how _you_ can [contribute](about#contribute). You can also [contact us](about#contact) find [help on using this TaxonPage website](https://github.com/SpeciesFileGroup/taxonpages/), where to [request a feature](https://github.com/SpeciesFileGroup/taxonpages/issues/new?assignees=&labels=enhancement&projects=&template=feature.yml) or [report a bug](https://github.com/SpeciesFileGroup/taxonpages/issues/new?assignees=&labels=bug&projects=&template=bug.yml&title=%5BBug%5D%3A+) or dive into the [technical details](/about#technical) behind the **{{project_name}}**.

## Announcements
### Announcement title 1
_ Authors, date_

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

### Announcement title 2
_ Authors, date_`

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

   
