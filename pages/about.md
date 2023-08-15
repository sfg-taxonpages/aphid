---
# See project.yml for variables.
---

# About

_{tag line}_

## Overview

The {{ app:project_name }} file offers a community-curated collection of richly-cited and annotated data on the taxonomy of Earth’s {{app:focal_taxon_common_name}}. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). See [Contribute](#contribute) for how you can participate. This site is built using TaxonPages, [learn more and get help](https://github.com/SpeciesFileGroup/taxonpages). For more on how this site is built please see the [Technical](#technical) section.

## Gaps as Opportunity

The Earth's biodiversity is vast, the data captured to describe it are minimal in comparison, but still immense. All projects of this nature contain gaps, i.e. opportunities for collaboration on future work, grants, and research. Known gaps in this project include {an incomplete catalog of type-material (important specimens that are linked to the names given to species}, {species names published after XXXX}, {biological associations}, {distributions from X} and more. [Contact us](#contribute) if you would like to help us address these, in particular we'd like to prioritize { choose from list above }.

## History

_Our old website is now a read-only resource available at [https://{{app:focal_taxon}}.archive.speciesfile.org](https://{{app:focal_taxon}}.archive.speciesfile.org)._

{How did the Species File Group come to be (shared history), perhaps point to https://speciesfilegroup.org}. How did this specific SF group come to be? When did we start our efforts? What are the historically important catalogs behind these data.}

As of {yyyy-mm-dd} all data in the former Species File Websites were frozen and shortly thereafter migrated to TaxonWorks. As with all migrations of this nature the process is both lossy (e.g. some data could not be mapped with certainty) and improved (e.g. semantics of the new models have more precision and clarity). The old website remains an excellent resource for fact-checking this migration. If you spot something that needs attention, please see [contribute](about#contribute)

## Team

### Contributors

_A \* denotes a past contributor, now inactive._
|name|role|
|----|----|
| First name Last Name | Author |
| First name Last Name\* | Author |
| First name Last Name | Editor |
| First name Last Name | TaxonWorks Project Manager |
| First name Last Name | Developer |
| First name Last Name | Community contributor |

### Contribute

_Projects of this nature require expertise in many different areas, not only on the taxa being treated. If you can imagine a way to contribute we'd love to hear about it._

- **{{ app:contact_email }}** is the primary way to contact us by email, including enquiries about joining the researchers building this Species File.
- Join the {{ app:project_name }} regular support meetings at { details if these exist }.
- Provide new data or to identify a problem with existing data: { {{ app:contact_email }} }, {Issue tracker option}.
- Report a technical bug (e.g. broken link or button) within TaxonPages: [TaxonPages' issue tracker](https://github.com/SpeciesFileGroup/taxonpages/issues/new?assignees=&labels=bug&projects=&template=bug.yml&title=%5BBug%5D%3A+)
- TaxonWorks and TaxonPages are open-source efforts that are [opportunities for you and others to join](https://docs.taxonworks.org/develop/contributing.html) to request new features, report bugs, or discuss use among other things.

### Governance

About our group structure, how the rules behind joining and participating are set.

### Support

_This Species File functionality and content is serviced in part by the Species File Group._

- {Society Logo } - Society
- Science Foundation {requires disclaimer}
- An organization other entity

#### Funding

Through the generous support of ... we ...
Or Funding needed to publish our latest information ... or address data gaps

### The Species File Group

#### The TaxonWorks Community

The work revealed on this website comes from many community meetings, many hours of research, a lot of software and data model development. This includes considerable effort to support impactful culture change and potentially enhanced standards of practice for data capture, sharing resources, knowledge, and workload. Please join the our community via the [Species File Group's regular Wednesday meetings](https://speciesfilegroup.org/events.html) to add your voice to our community and learn more.

## Extended access

_A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals._

- Researchers working on this project use their rich, multi-faceted access to the data via TaxonWorks' interfaces (e.g. filters, reporting, downloads). Access requires a project account, see [Contribute][#contribute].
- Data behind individual panels can be seen via the _SiteMap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other data not available here are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1),
- Core taxonomic data are exported to and available at the [Catalogue of Life]({https://link_to_root_taxon_page}) and its [associated API](https://link_to_api_for_pertinent_dataset).

## Technical

Want to create your own site? This website is built completely using open-source software. Data are curated in a TaxonWorks project then shared via a TaxonWorks API. TaxonPages accesses these shared data and renders it into the panels and pages you see here.

## Related resources

_Find out more about {{ app:focal_taxon }} at these websites._

### Websites

- [site name]{site url}
- [site name]{site url}

### References

- Citation. [Citation link](doi)

## Terms of Use (Copyright Guidance)

Except where noted, content on this site licensed under the terms of the [Creative Commons Attribution License (CC-BY)](LINK). Images and other media, except where noted, please use under the [CC BY](LINK) license.
