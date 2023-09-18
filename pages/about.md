# About
_{{ app:project_name }} is a community-built open resource on the aphids of the world_

## Overview
_{{ app:project_name }}_ offers a community-curated collection of cited and annotated information on the taxonomy of Earth’s aphids, including {{app:focal_taxon_common_name}}. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). See [Contribute](#contribute-or-get-help) for how you can participate. This site is built using TaxonPages, [learn more and get help](https://github.com/SpeciesFileGroup/taxonpages). For more on how this site is built please see the [Software](#software) section.

## Gaps as opportunity
The Earth's biodiversity is vast, the data captured to describe it are minimal in comparison, but still immense. All projects of this nature contain gaps, i.e. opportunities for collaboration on future work, grants, and research. A particularly important gap in this project concerns specimen data. From specimen data, we can then fill in gaps regarding include biological associations}, {distributions from X} and more. [Contact us](#contribute-or-get-help) if you would like to help us address these, in particular we'd like to prioritize { choose from list above }.

## History
_Our old website is now a read-only resource available at [http://{{app:focal_taxon}}.archive.speciesfile.org](https://{{app:focal_taxon}}.archive.speciesfile.org)._

_{{ app:project_name }}_ started in 2008 and was introduced to the aphid knowledge community at the International Symposium on Aphids in Katania, Italy, in 2009. [Favret C, Eades DC. 2009. Introduction to Aphid Species File, http://Aphid.SpeciesFile.org. Redia, 92: 115-117.](https://www.redia.it/images/stories/pdf2009/21%20Favret.pdf).

Until August 2023, _{{ app:project_name }}_ was almost entirely curated by [{{app:project_authors}}](http://favret.aphidnet.org/en/principal-investigator/). At that time, all data in _{{ app:project_name }}_ were frozen and migrated to TaxonWorks. With this renewal, the call is out to colleagues worldwide. Please contact us if you would like to contribute. [Contribute or get help](#contribute-or-get-help).

## Contributors
|name|affiliation|role|identifier|
|:----|:----|:----|:----|
| {{app:project_authors}} | University of Montreal, Canada | Author | [ORCiD](https://orcid.org/0000-0001-6243-3184) |
| Gary L. MILLER | Systematic Entomology Laboratory, US Department of Agriculture | Contributor | [ORCiD](https://orcid.org/0000-0001-5456-8097) |
| QIAO Gexia | Institute of Zoology, Chinese Academy of Sciences | Contributor | [ORCiD](https://orcid.org/0000-0002-7300-6812) |
| Masakazu SANO | Hokkaido Agricultural Research Center, NARO, Japan | Contributor | [ORCiD](https://orcid.org/0000-0001-7477-2570) |
| Andrey V. STEKOLSHCHIKOV | Zoological Institute, Russian Academy of Sciences | Contributor | [ORCiD](https://orcid.org/0000-0003-4168-7649) |

### Support and funding
_This Species File functionality and content is serviced in part by the Species File Group._

## Contribute or get help
_Projects of this nature require expertise in many different areas, not only on the taxa being treated. If you can imagine a way to contribute we'd love to hear about it._

- **<a href="mailto:{{app:contact_email}}">Email</a>** is the primary way to contact us, including enquiries about **joining** the researchers building this Species File. { ... or join a regular support meeting. } { See also [Governance](#governance). }
- **Provide new data or identify a problem with existing data** by contacting us (see above). { Alternate data manager email}, {Issue tracker option}.
- **Cite** this website via the citation at the bottom of the page. See also [Terms of use](#terms-of-use-and-copyright-guidance).
- **Something is broken** (i.e. with TaxonPages the software)? See [Software](#software), or use the [TaxonPages Issue Tracker](https://github.com/SpeciesFileGroup/taxonpages/issues).

### Extended data access
_A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals._

- Researchers working on this project use their rich, multi-faceted access to the data via TaxonWorks' interfaces (e.g. filters, reporting, downloads). Access requires a project account, see [Contribute or get help](#contribute-or-get-help).
- Data behind individual panels per page can be seen via the _Sitemap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other information not available on these pages are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1).
- Core taxonomic data are exported to and available at the [Catalogue of Life]({https://link_to_root_taxon_page}) and its [associated API]({https://link_to_api_for_pertinent_dataset}).

### References

* [Favret C, Havill NP, Miller GL, Sano M, Victor B (2015) Catalog of the adelgids of the world (Hemiptera, Adelgidae). ZooKeys 534: 35-54.](https://doi.org/10.3897/zookeys.534.6456)
* [Favret C, Blackman RL, Miller GL, Victor B (2016) Catalog of the phylloxerids of the world (Hemiptera, Phylloxeridae). ZooKeys 629: 83-101.](https://doi.org/10.3897/zookeys.629.10709)

## Related resource

|Name|URL|Note|
|:----|:---|:----|
| Aphids on the World's Plants: an  online identification and information guide | [Aphids on the World's Plants](http://www.aphidsonworldsplants.info/) | created by [Roger BLACKMAN](https://doi.org/10.11646/zootaxa.5183.1.4), maintained by {{app:project_authors}} |

## Terms of use and copyright guidance

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

