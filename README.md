# longterm_phenology_climate

This repo contains scripts used to create maps of the study site and analyze climate data as part of my study on climate sensitivity of Potentilla flowering time using long-term phenology data from RMBL field station. The scripts:

- 01: create maps of the study sites and surrounding area
- 02: prepare climate data (using billy barr RMBL weather station, PRISM, and SNOTEL sources):
    - (a) convert snowmelt into a Julian date format for analysis, 
    - (b) prepare PRISM estimates of temperature and precipitation, assess correlation with other climate variables
    - (c) compare two different climate data sources (PRISM, SNOTEL) to validate my use of the longer-term PRISM data with the SNOTEL data from stations bracketing the study site
- 03: create multivariate climate axes using PCA, for subsequent analyses
