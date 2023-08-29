---
# See project.yml for variables.
---
# About
_{tag line- e.g. "Building community around and gathering knowledge about the world’s stoneflies"}_

## Overview
The _{{ app:project_name }}_ file offers a community-curated collection of richly-cited and annotated information on the taxonomy of Earth’s {{app:focal_taxon_common_name}}. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). See [Contribute](#contribute-or-get-help) for how you can participate. This site is built using TaxonPages, [learn more and get help](https://github.com/SpeciesFileGroup/taxonpages). For more on how this site is built please see the [Software](#software) section.

## Gaps as opportunity
The Earth's biodiversity is vast, the data captured to describe it are minimal in comparison, but still immense. All projects of this nature contain gaps, i.e. opportunities for collaboration on future work, grants, and research. Known gaps in this project include {an incomplete catalog of type-material (important specimens that are linked to the names given to species}, {species names published after XXXX}, {biological associations}, {distributions from X} and more. [Contact us](#contribute-or-get-help) if you would like to help us address these, in particular we'd like to prioritize { choose from list above }.

## History
_Our old website is now a read-only resource available at [https://{{app:focal_taxon}}.archive.speciesfile.org](https://{{app:focal_taxon}}.archive.speciesfile.org)._

{How did this specific SF group come to be? When did we start our efforts? What are the historically important catalogs behind these data. Potentially linked to a shared history at sfg.org if we get that done.}

As of August 2023 all data in the former Species File Websites were frozen and shortly thereafter migrated to TaxonWorks. As with all migrations of this nature the process is both lossy (e.g. some data could not be mapped with certainty) and improved (e.g. semantics of the new models have more precision and clarity). The old website remains an excellent resource for fact-checking this migration. If you spot something that needs attention, please see [Contribute or get help](#contribute-or-get-help).

### Support and funding
_This Species File functionality and content is serviced in part by the Species File Group._

Through the generous support of ... we ...
Or Funding needed to publish our latest information ... or address data gaps

- {Society Logo } - Society
- Science Foundation {requires disclaimer}
- An organization other entity

## Contributors

|name|role|
|----|----|
| First name Last Name | Author |
| First name Last Name\* | Author |
| First name Last Name | Editor |
| First name Last Name | TaxonWorks Project Manager |
| First name Last Name | Developer |
| First name Last Name | Community contributor |

_A \* denotes a past contributor, now inactive._

## Contribute or get help
_Projects of this nature require expertise in many different areas, not only on the taxa being treated. If you can imagine a way to contribute we'd love to hear about it._

- **<a href="mailto:{{app:contact_email}}">Email</a>** is the primary way to contact us, including enquiries about **joining** the researchers building this Species File. { ... or join a regular support meeting. } { See also [Governance](#governance). }
- **Provide new data or identify a problem with existing data** by contacting us (see above). { Alternate data manager email}, {Issue tracker option}.
- **Cite** this website via the citation at the bottom of the page. See also [Terms of use](#terms-of-use).
- **Something is broken** (i.e. with TaxonPages the software)? See [Software](#software), or use the [TaxonPages Issue Tracker](https://github.com/SpeciesFileGroup/taxonpages/issues).

### Extended data access
_A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals._

- Researchers working on this project use their rich, multi-faceted access to the data via TaxonWorks' interfaces (e.g. filters, reporting, downloads). Access requires a project account, see [Contribute or get help](#contribute-or-get-help).
- Data behind individual panels per page can be seen via the _Sitemap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other information not available on these pages are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1).
- Core taxonomic data are exported to and available at the [Catalogue of Life]({https://link_to_root_taxon_page}) and its [associated API]({https://link_to_api_for_pertinent_dataset}).

### Software
These pages are built with completely open-source software. [Read more](http://speciesfilegroup.org/docs/taxonworks_in_production_at_sfg.html) about what drives them, how they supported by the Species File Group and their many collaborators, or [join weekly support meetings](https://speciesfilegroup.org/events.html) and see how it all fits together, includes links to issue trackers.

### Governance
About our group structure, how the rules behind joining and participating are set.

## Related resources

### References

* { Some typical reference cited format } 

### Websites

|Name|URL|Note|
|----|---|----|
| Site name | [site name]{site url} | Note |
| Site name | [site name]{site url} | Note |

## Terms of use (Copyright guidance)

<div class="flex items-center gap-2">
  <a
    class="min-w-fit"
    href="{{ app:copyright_image_link }}"
  >
    <img 
      src="{{ app:copyright_image }}" 
      alt="copyright" 
      class="m-0"
    >
  </a>
  <span>{{ app:copyright_text }}</span>
</div>

