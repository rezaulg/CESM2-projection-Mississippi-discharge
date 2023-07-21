# CESM2-projection-Mississippi-discharge
This repository contains the scripts that I have developed to assess the climate change impact on 21st century Mississippi River discharge using projections from CESM2 large ensembles.

The input data needed to produce the figures for the paper are:
For Discharge:
Latitude and Longitude input files: (i) latsUsArr.npy and (ii) lonsUsArr.npy
Data input files: (i) monDischUsHistSelEnsMean.npy and (ii) monDischUsScenEnsMean.npy

For each of the variables other than discharge:
Latitude and Longitude input files: (i) latsUsArr.npy and (ii) lonsUsArr.npy
Data input files: (i) monParamUsHistSelEnsMean.npy and (ii) monParamUsScenEnsMean.npy

Here, ‘Param’ within the name of the *.npy data input file refers to Precip, Et, SnowMelt, SoilMoist, and Runoff for Precipitation, Evapotranspiration, Snowmelt, Soil Moisture, and Runoff dataset, respectively.

The data files (e.g., monDischUsHistSelEnsMean.npy for discharge) and Latitude, Longitude information files for each parameter (e.g., Discharge, Precipitation, ET, Snowmelt, Soil Moisture, and Runoff) are produced by running the scripts for each parameter stored within the “dataScript” folder of the repository. These *.npy files must be prepared first by running the scripts using “GLADE” access to NCAR HPC system and then must replace the *.npy input files in the respective scripts to produce each figure.

