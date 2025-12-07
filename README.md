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

 - [3]Biodiversity Intactness Index (BII) Time Series
 Source: https://planetarycomputer.microsoft.com/dataset/io-biodiversity
 This data will be accessed remotely, and does not need to be downloaded
 
 
 
 - [4]Arizona State Count Subdivision Shapefile
 Source: https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision
 This data will need to be downloaded and put into the a folder titled `data` within the repository base

### References

[1] Z. Levitt and J. Eng, “Where America’s developed areas are growing: ‘Way off into the horizon’,” The Washington Post, Aug. 2021. Available: https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/. [Accessed: Nov. 22, 2024]

[2] F. Gassert, J. Mazzarello, and S. Hyde, “Global 100m Projections of Biodiversity Intactness for the years 2017-2020 [Technical Whitepaper],” Aug. 2022. Available: https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io-biodiversity/Biodiversity_Intactness_whitepaper.pdf. [Accessed: Dec. 6, 2025]

[3] Microsoft Planetary Computer, “Biodiversity Intactness Index (BII) Time Series,” Available: https://planetarycomputer.microsoft.com/dataset/io-biodiversity. [Accessed: Dec. 6, 2025]

[4] U.S. Census Bureau, “TIGER/Line Shapefile: Current State of Arizona County Subdivision,” Data.gov, Available: https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision. [Accessed: Dec. 6, 2025]