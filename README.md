# HyTES

The Hyperspectral Thermal Emission Spectrometer (HyTES) is an airborne imaging spectrometer with 256 spectral channels between 7.5 and 12 micrometers in the thermal infrared part of the electromagnetic spectrum and 512 pixels cross-track (https://hytes.jpl.nasa.gov/). 

The scripts here downdload flight information and create GeoTIFF for the Land Surface Temperature from HyTES. Information of individual fight is avialable at JPL's website, but I needed information of all the flights. Note that as of June 2020, the information in the header file may not exactly match the data format in the HDF file. You will have to reach out to the team at JPL if you need any help. 
