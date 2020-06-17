---
layout: lesson
root: .
---

Data Carpentry's aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain.


Interested in teaching these materials? We have an [onboarding video](https://www.youtube.com/watch?v=Qtnb_eeHt7E) available to prepare Instructors to teach these lessons. After
watching this video, please contact [team@carpentries.org](mailto:team@carpentries.org) so that we can record your status as an onboarded
Instructor. Instructors who have completed onboarding will be given priority status for teaching at centrally-organized Data Carpentry Geospatial workshops.


> ## Getting Started
>
> Data Carpentry’s teaching is hands-on, so participants are encouraged to use
> their own computers to ensure the proper setup of tools for an efficient
> workflow. To most effectively use these materials, please make sure to download
> the data and install everything before working through this lesson.
>
> This workshop assumes no prior experience with the tools covered in the workshop. However, learners with prior
> experience working with geospatial data may be able to skip the
> [Geospatial Project Organization and Management](https://www.datacarpentry.org/organization-geospatial/) lesson.
> Similarly, learners who have prior experience with the `R` programming language may wish to skip the
> [Introduction to R for Geospatial Data](https://www.datacarpentry.org/r-intro-geospatial/) lesson.
>
> To get started, follow the directions in the [Setup](setup.html) tab to
> get access to the required software and data for this workshop.
{: .prereq}

> ## Data
>
> The data and lessons in this workshop were originally developed through a hackathon funded by the
> [National Ecological Observatory Network (NEON)](https://www.neonscience.org/) - an NSF funded observatory in Boulder, Colorado - in
> collaboration with Data Carpentry, SESYNC and CYVERSE. NEON is collecting data for 30 years to help scientists understand
> how aquatic and terrestrial ecosystems are changing. The data used in these lessons cover two NEON field sites:
> * Harvard Forest (HARV) - Massachusetts, USA - [fieldsite description](https://www.neonscience.org/field-sites/field-sites-map/HARV)
> * San Joaquin Experimental Range (SJER) - California, USA - [fieldsite description](https://www.neonscience.org/field-sites/field-sites-map/SJER)
>
> The data for this workshop are available
> [on Figshare](https://figshare.com/articles/Geospatial_Data_Carpentry_Workshop_Data_Subset/12473486)
> under a CC-BY license. This is a reduced subset of the original data publication by Wasser and Jones (2016). You can download all of the data used in this workshop by clicking
> [this download link](https://ndownloader.figshare.com/files/23104040).
> Clicking the download link will download all of the files as a single compressed
> (`.zip`) file. To expand this file, double click the folder icon in your file navigator application (for Macs, this is the Finder
> application).
>
> These data files represent teaching version of the data, with sufficient complexity to teach many aspects of  data analysis and
> management, but with many complexities removed to allow students to focus on the core ideas and skills being taught.
>
> | Dataset | Folder or file name | Description |
> | ---- | ------| ---- |
> | Site layout shapefiles | "vector" folder | A set of shapefiles for the NEON's Harvard Forest field site and US and (some) state boundary layers. |
> | Airborne remote sensing data | "raster" folder | LiDAR data collected by the NEON Airborne Observation Platform (AOP) and processed at NEON including a canopy height model, digital elevation model and digital surface model for NEON's Harvard Forest and San Joaquin Experimental Range field sites. |
> | Point locations of field plots | .csv files | Two files that contain geographic coordinates of plot locations in the Harvard Forest field sites |
>
> [More information on this dataset](data)
>
{: .prereq}

# Workshop Overview

| Lesson    | Overview |
| ------- | ---------- |
| [Introduction to Geospatial Concepts](https://uw-madison-datascience.github.io/organization-geospatial/) | Understand data structures and common storage and transfer formats for spatial data. |
| [Introduction to R for Geospatial Data](https://uw-madison-datascience.github.io/r-intro-geospatial) | Import data into R, calculate summary statistics, and create publication-quality graphics. |
| [Introduction to Geospatial Raster and Vector Data with R](https://uw-madison-datascience.github.io/r-raster-vector-geospatial) | Open, work with, and plot vector and raster-format spatial data in R. |
