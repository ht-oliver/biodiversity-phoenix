# Urban Development and Biodiversity Intactness in Phoenix, Arizona
###### Author: Henry Oliver

### About
The purpose of this exercise is to learn bout calculating values from rasters in specific areas using python. We will do this by taking a look at the loss in Biodiversity in Phoenix, Arizona.

In 2021, Maricopa County —home to the Phoenix metropolitan area— was identified as the U.S. county with the most significant increase in developed land since 2001 [1]. This rapid urban sprawl has profound implications for biodiversity and the health of surrounding natural ecosystems.

### Repository Structure
The `data` folder in this repository is empty, but should be populated as indicated below once data has been downloaded. See the 'Data' section in this READme for more information

```
├── README.md
├── analysis.ipynb # Document containing analysis
└── data  # This folder does not exist, but should be created and populated as indicated below
    └── tl_2024_04_cousub
        ├── tl_2024_04_cousub.cpg
        ├── tl_2024_04_cousub.dbf
        ├── tl_2024_04_cousub.prj
        ├── tl_2024_04_cousub.shp
        ├── tl_2024_04_cousub.shp.ea.iso.xml
        ├── tl_2024_04_cousub.shp.iso.xml
        └── tl_2024_04_cousub.shx
```

### Data

 - Biodiversity Intactness Index (BII) Time Series
 Source: https://planetarycomputer.microsoft.com/dataset/io-biodiversity
 This data will be accessed remotely, and does not need to be downloaded
 
 
 
 - Arizona State Count Subdivision Shapefile
 Source: https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision
 This data will need to be downloaded and put into the a folder titled `data` within the repository base

### References

**Biodiversity Intactness Index (BII) Time Series**
Microsoft Planetary Computer. (n.d.). Biodiversity Intactness Index (BII) Time Series. Retrieved December 6, 2025, from https://planetarycomputer.microsoft.com/dataset/io-biodiversity

**Arizona State County Subdivision Shapefile**
U.S. Census Bureau. (n.d.). TIGER/Line Shapefile: Current State of Arizona County Subdivision. Data.gov. Retrieved December 6, 2025, from https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision