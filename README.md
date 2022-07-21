# Cleaning of field guide data

This repository contains the raw data of 18 bird field guides and two sets of scripts (markdowns, both in .Rmd and knitted .html format).

- `fielguide_merging.Rmd` : takes the content of the `data/raw_data` folder and merges it all into one file; spits out `voice_all_guides.csv`

- `IOC_list_merging.Rmd` : takes the combined field guide data frame `voice_all_guides.csv` and merges it with the IOC world bird list `master_ioc_list_v12.1.csv`; spits out three files: 1) `voice_all_guides_with_ioc.csv`, which is the field guide data with family, order, and English common names from the IOC, 2) `master_ioc_list_v12.1_cleaned.csv`, which is an easier-to-work-with version of the IOC list, and 3) a list of counts of Latin species names `all_guides_species_counts.csv` that should make it easier to identify typos

