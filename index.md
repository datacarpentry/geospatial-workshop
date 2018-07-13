---
layout: lesson
root: .
---

Data Carpentry's aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain. 

> ## Getting Started
>
> This lesson assumes no prior experience with the tools covered in the workshop.
> Participants should bring their laptops and plan to participate actively.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
>
> Please note that workshop materials for working with Geospatial data in R are under development and will become available
> in July 2018.
{: .prereq}

> ## Data
> The data and lessons in this workshop were originally developed through a hackathon funded by the 
> [National Ecological Observatory Network (NEON)](https://www.neonscience.org/) - an NSF funded observatory in Boulder, Colorado - in 
> collaboration with Data Carpentry, SESYNC and CYVERSE. NEON is collecting data for 30 years to help scientists understand
> how our aquatic and terrestrial ecosystems are changing. The data used in these lessons cover two NEON field sites:  
> * Harvard Forest (HARV) - Massachusetts, USA - [fieldsite description](https://www.neonscience.org/field-sites/field-sites-map/HARV)
> * San Joaquin Experimental Range (SJER) - California, USA - [fieldsite description](https://www.neonscience.org/field-sites/field-sites-map/SJER)
> 
> There are four data sets included, all of which are available 
> [on Figshare](https://figshare.com/articles/Spatio_temporal_Series_Teaching_Data_Subsets/2009586)
> under a CC-BY license. You can download all of the data used in this workshop by clicking 
> [this download link](https://ndownloader.figshare.com/articles/2009586/versions/10). 
> Clicking the download link will automatically download all of the files to your default download directory as a single compressed
> (`.zip`) file. To expand this file, double click the folder icon in your file navigator application (for Macs, this is the Finder 
> application).
> 
> These data files represent teaching version of the data, with sufficient complexity to teach many aspects of  data analysis and 
> management, but with many complexities removed to allow students to focus on the core ideas and skills being taught.  
> 
> | Dataset | File name | Description |
> | ---- | ------| ---- | 
> | Site layout shapefiles | NEON-DS-Site-Layout-Files.zip | A set of shapefiles for the NEON's Harvard Forest field site and US and (some) state boundary layers. | 
> | Meteorological data |  NEON-DS-Met-Time-Series.zip | Precipitation, temperature and other variables collected from a flux tower at the NEON Harvard Forest site
> | Airborne remote sensing data | NEON-DS-Airborne-RemoteSensing.zip | LiDAR data collected by the NEON Airborne Observation Platform (AOP) and processed at NEON including a canopy height model, digital elevation model and digital surface model for NEON's Harvard Forest and San Joaquin Experimental Range field sites. | 
> | Landstat 7 NDVI raster data | NEON-DS-Landsat-NDVI.zip | 2011 NDVI data product derived from Landsat 7 and processed by USGS cropped to NEON's Harvard Forest and San Joaquin Experimental Range field sites | 
> 
> [More information on this dataset](data)
> 
{: .prereq} 

The workshop is taught using R.


# Workshop Overview

| Lesson    | Overview |
| ------- | ---------- |
| [Geospatial Project Organization and Management](http://www.datacarpentry.org/organization-geospatial/) | Understand data structures and common storage and transfer formats for spatial data. |
| [Introduction to R for Geospatial Data](http://www.datacarpentry.org/r-intro-geospatial) | Import data into R, calculate summary statistics, and create publication-quality graphics. |
| [R for Raster and Vector Data](http://www.datacarpentry.org/r-raster-vector-geospatial) | Open, work with, and plot vector and raster-format spatial data in R. |
