# Where Can I Farm this Species? Exploring Aquaculture Suitability on the West Coast
## EDS223 Homework 4

This repository contains the response to Homework 4 in EDS223 - *Geospatial Analysis & Remote Sensing*, completed by Sofia Sarak.

In the growing world of aquaculture, knowing where a species will thrive is vital. The analysis contained in this repository aims to determine which areas of the west coast of the United States are the best suited for a variety of aquaculture species. This is done through the utilization of spatial raster and vector data as well as species-specific requirements.

The outputs of this workflow are a map of the West Coast exclusive economic zones ranked by aquaculture suitability for oysters, a map with the same information for bull kelp, and a generalized function that produces such maps using arguments for species name, temperature range, and depth range (under the assumption that the data is pre-loaded and properly prepared). 

For more information on the homework assignment itself (including all of the data and sources), reference the [assignment description](https://eds-223-geospatial.github.io/assignments/HW4.html#fn3).

## Data Sources

**Sea Surface Temperature**

This analysis uses average annual sea surface temperature (SST) from the years 2008 to 2012. The data was originally generated from [NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).

**Bathymetry**

Bathymetry, or ocean depth data, is provided in meters from the [General Bathymetric Chart of the Oceans (GEBCO)](https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area)

**Exclusive Economic Zones**

An exclusive economic zone (eez) is "an area of coastal water and seabed within a certain distance of a country's coastline, to which the country claims exclusive rights for fishing, drilling, and other economic activities" ([Oxford Languages](https://languages.oup.com/dictionaries/)).

Our eez data is specifically for the west coast of the United States and comes from [Marineregions.org](https://www.marineregions.org/eez.php).

*Information on data sources was retrieved from original assignment description.*

## Repository Structure
```
├── README.md
├── west_coast_eez.Rproj
├── west_coast_eezs.pdf
├── west_coast_eezs.qmd
├── images
│   ├── bull_kelp.jpg
│   └── oysters.jpeg
├── .gitignore
│   ├── data
│       ├── average_annual_sst_2008.tif
│       ├── average_annual_sst_2009.tif
│       ├── average_annual_sst_2010.tif
│       ├── average_annual_sst_2011.tif
│       ├── average_annual_sst_2012.tif
│       ├── depth.tif
│       ├── wc_regions_clean.dbf
│       ├── wc_regions_clean.prj
│       ├── wc_regions_clean.shp
│       └── wc_regions_clean.shx

```
## Course Information

-   **Course Title:** [EDS 223 - Geospatial Analysis & Remote Sensing](https://eds-223-geospatial.github.io/)
-   **Term:** Fall 2025
-   **Program:** [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

Teaching Team:

-   **Instructor:** [Annie Adams](https://github.com/annieradams)
-   **Teaching Assistant:** Alessandra Vidal Meza

Complete materials for the discussion sections and additional resources can be found on the [course website](https://eds-223-geospatial.github.io/).

*This README was adapted from the README template provided in EDS220; see course details and original repository [here](https://github.com/sofiasarak/eds220-2025-in-class).*
