# Intro
This repository provides a guide on how to turn NEXRAD Radar data into NETCDF gridded datasets. The [Jupyter notebook](./Creating_NetCDF_from_Radar.ipynb) contains the steps required to produce NETCDF outputs.

## Tools Required
Note that external tools beyond python are required. Googles command line interface is needed to access compressed NEXRAD data. The [Weather Climate Toolkit (WCT)](https://www.ncei.noaa.gov/products/weather-climate-toolkit) from NOAA is needed to convet the raw radar files into NETCDF files. Depending on the number of days converted, use of a ram disk can be recommended.

# Likely Issues
* The extraction step for tar.Z and tar.gz files was designed to work with MacOS and may not function on Windows. 
* The WCT workflow was designed for Windows and will have to be modified to run on MacOS or Linux. 
