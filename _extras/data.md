---
layout: page
title: "Workshop data"
---

## Geospatial Data Carpentry Workshop Data Subset

Available on FigShare: 
[Geospatial Data Carpentry Workshop Data Subset](https://figshare.com/articles/Geospatial_Data_Carpentry_Workshop_Data_Subset/12473486).

**CITATION:** Data Skills Teaching Data Subsets, NEON; Wasser, Leah; Jones, Megan A. (2016): 
NEON Spatio-temporal Teaching Data Subset. figshare. Fileset. https://doi.org/10.6084/m9.figshare.2009586.v10 

Please note that the data provided here are a subset of the original Data Skills Teaching Data Subsets created by NEON, Leah Wasser, and Megan Jones. The original teaching data subset can be downloaded from the link provided in the citation.

The data and lessons in this workshop were originally developed through a hackathon funded by the [National Ecological Observatory Network (NEON)](https://www.neonscience.org/) - an NSF funded observatory in Boulder, Colorado - in collaboration with Data Carpentry, SESYNC and CYVERSE. NEON is collecting data for 30 years to help scientists understand
how our aquatic and terrestrial ecosystems are changing. The data used in these lessons cover two NEON field sites:
* Harvard Forest (HARV) - Massachusetts, USA - [fieldsite description](https://www.neonscience.org/field-sites/field-sites-map/HARV)
* San Joaquin Experimental Range (SJER) - California, USA - [fieldsite description](https://www.neonscience.org/field-sites/field-sites-map/SJER)
 
The data for this workshop are available [on Figshare](https://figshare.com/articles/Geospatial_Data_Carpentry_Workshop_Data_Subset/12473486) under a CC-BY license. This is a reduced subset of the original data publication by Wasser and Jones (2016). You can download all of the data used in this workshop by clicking [this download link](https://ndownloader.figshare.com/files/23135981).

Clicking the download link will download all of the files as a single compressed (`.zip`) file. To expand this file, double click the folder icon in your file navigator application (for Macs, this is the Finder application).

These data files represent teaching version of the data, with sufficient complexity to teach many aspects of  data analysis and management, but with many complexities removed to allow students to focus on the core ideas and skills being taught.

| Dataset | Folder or file name | Description |
| ---- | ------| ---- |
| Site layout shapefiles | "vector" folder | A set of shapefiles for the NEON's Harvard Forest field site and US and (some) state boundary layers. |
| Airborne remote sensing data | "raster" folder | LiDAR data collected by the NEON Airborne Observation Platform (AOP) and processed at NEON including a canopy height model, digital elevation model and digital surface model for NEON's Harvard Forest and San Joaquin Experimental Range field sites. |
| Point locations of field plots | .csv files | Two files that contain geographic coordinates of plot locations in the Harvard Forest field sites |


### About the Site Layout Shapefiles
These vector data provide information on the site characterization and infrastructure at the 
[National Ecological Observatory Network's](https://www.neonscience.org/)
[Harvard Forest](https://www.neonscience.org/field-sites/field-sites-map/HARV) field site. 
The Harvard Forest shapefiles are from the [Harvard Forest GIS & Map](http://harvardforest.fas.harvard.edu/gis-maps/) archives. 
US Country and State Boundary layers are from the [US Census Bureau](https://www.census.gov/geo/maps-data/data/tiger-cart-boundary.html).

### About the Airborne Remote Sensing Data
This data was collected at the [National Ecological Observatory Network's](https://www.neonscience.org/) 
[Harvard Forest](https://www.neonscience.org/field-sites/field-sites-map/HARV) and 
[San Joaquin Experimental Range](https://www.neonscience.org/field-sites/field-sites-map/SJER) field sites. 

Data are collected during peak greenness at each field site and are processed to provide useful data products to the community. The following NEON data products are used in these lessons:

Data Created from Discrete Return (point clouds) Lidar Data:

* DSM (Digital Surface Model; full mosaic)
* DTM (Digital Terrain Model; full mosaic)
* CHM (Canopy Height Model; full mosaic; Harvard Forest site only)
and
* RGB imagery (Harvard Forest site only) derived from the RGB Camera

Additional information about airborne remote sensing data, including other data types for these and other sites can
be found on [NEON’s Airborne Data](https://www.neonscience.org/data-collection/airborne-remote-sensing) page.
