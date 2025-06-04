# ISNU World War I Service Records
This repository contains data related to the [World War I Illinois State Normal University Service Records](https://cdm15990.contentdm.oclc.org/digital/collection/WWI_records/search) digital collection. 

## Raw Data
`raw-collection-metadata.csv` contains the raw, page-level, unprocessed metadata exported from the digital collection, including all transcripts (see the **Transcript** column).

## ArcGIS Data files
These are the data files used to create mapping visualizations in ArcGIS. They were derived from the raw colleciton metadata in `raw-collection-metadata.csv` and restructured (using OpenRefine) to create a dataset listing one-location-per-row. Because many individuals described by the collection traveled to multiple places, there may be multiple rows per person. These data files were used to create the visualizations in the [Over There](https://storymaps.arcgis.com/collections/c6c1bc19ebdf41548f9fd8662c1ff1e0) StoryMaps exhibit.

* `WWI_all.csv` is the comprehensive, location-level dataset listing all visits to locations by ISNU affiliates
* `battles.csv` is limited to locations of battles associated with ISNU affiliates
* `gold-star.csv` is limited to locations of fatalities
* `influenza.csv` is limited to locations of influenza hospitalizations
* `women.csv` is limited to locations visited by women in the collection
* `count-by-location.csv` compiles the number of visits to each location throughout the collection

## Documentation
This folder contains documentation used in the creation of the digital collection.
