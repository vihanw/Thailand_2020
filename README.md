# Thailand_2020
Collection of IPython scripts used for accessing remote sensed data from NASA servers and scripts used for post processing flood simulation results from CFAST

# Table of Contents
## IFDCurvesGeneration
#### Generate_IFD_Bangkok.ipynb -  
* Extracts GPM IMERG Rainfall data for a specified sub region from the NASA GES DISC THREDDS SERVER and plots IFD Curves

## RainfallDataForSimulation
### APHRODITE_Data - 
#### ReadnetCDFData.ipynb - 
* Reads netCDF data from the APHRODITE Website (aphrodite.st.hirosaki-u.ac.jp) and plotting the data for a specified region

### GPMIMERG_Data 
#### Get_netCDF_data.ipynb -
* Extracts GPM IMERG data for a specified duration, combines the data and plot the data for a specified region

## ResultsPostProcessing
### DesignSLRCase 
#### SLRComparison.ipynb - 
* Combines flood height rasters from CFAST results to compare increasing flood extents due to sea-level rise

### ValidationCasePostProcessing
#### ThailandPostProcessing.ipynb -
* Script to process flood simualtion results from the validation simulations (flood event in 2011) and compaare the results with the historical data

## InfiltrationDataExtraction
#### ExtractGTIFFFromNetCDF.ipynb -
Script to read the GLDAS soil types netCDF data and map it to the Green Ampt infiltration parameters and save the parameters as geotiffs
