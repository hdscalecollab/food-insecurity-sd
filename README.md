# food-insecurity-sd
This repository hosts code snippets of analysis and data for the Asian food insecurity project in San Diego

- Paper reference:
    - Xie, R., Cao, Y., Yang J-A., Tribby, C. P., Voong, C., and Jankowska, M. M.. *Measuring Access to Culturally Appropriate Food and Associations with Diabetes among Asian Americans.* (in review)

- For questions, please contact Rujia Xie (rujiaxie5@gmail.com)


## Overview of Analysis Workflow


## File Structures in This Repository
- `AsianFoodAccess_R.Rmd` contains the full R code used for statistical and spatial analysis in this study.

- `FullDataset_Final.xlsx` is the excel file with all the CT-level variables that were imported to R for analysis. 

- `FullDatasetNew.xlsx` is the excel file that contains both the original variables and the OLS residuals generated by R. It was imported to ArcGIS to test the spatial autocorrelation of the OLS residuals.

- `SpatialDataset.shp` is the shapefile generated by importing _FullDatasetNew.xlsx_ to ArcGIS. It was imported to R to calculate Spatial Lag Regression. 

- `FullDatasetSpatial.xlsx` is the excel file generated by R that contains both the original variables, the OLS residuals, and the SLR residuals, which was imported into ArcGIS to see the spatial autocorrelation of the SLR residuals.
