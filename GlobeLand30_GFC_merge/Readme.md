In progress...  
## Synopsis
This geoprocessing model merges GlobeLand30 and Global Forest Change geodata into a single LandCover raster. Performing cell resampling and alligment to SRTM 1sec DEM.
  
## Environment Setup
To run the model: ArcGIS 10.4.1 with Spatial Analyst extension. ArcGIS ".tbx" contains the model.    

## Model input and execution
Please see a ".png" screenshots in this repository to correctly specify the geoprocessing model input. 
Test data in this folder can be used to execute the geoprocessing model.  
Ignore the "Define projection" message for GlobeLand30 layer. It is not necesarry, but it is performed to write a projection in the ArcGIS heading format for this geodata.  
After the model execution, in ArcMap for the LandCover_clip.tif layer, the symbology should be specified. To observe the correct raster symbology, In the Symbology tab for the Unique values import the LandCover.lyr file, that is localed in the data input folder (this is ArcGIS ModelBuilder limitation). 

## References
CHEN, J., CHEN, J., LIAO, A., CAO, X., CHEN, L., CHEN, X, HE, C., HAN, G., PENG, S., LU, M., ZHANG, W., TONG, X., MILLS, J. (2015). Global land cover mapping at 30 m resolution: A POK-based operational approach. ISPRS Journal of Photogrammetry and Remote Sensing, Vol. 103, 7–27. [Online]. Data available: http://www.globallandcover.com/GLC30Download

HANSEN, M.C., POTAPOV, P., MOORE, R., et al. (2013a). High-resolution global maps of 21st-century forest cover change. Science, 342, 850–853. [Online]. Data available: https://earthenginepartners.appspot.com/science-2013-global-forest

NASA JPL. (2013). NASA Shuttle Radar Topography Mission Global 1 arc second. NASA LP DAAC. Data available: e4ftl01.cr.usgs.gov/SRTM/SRTMGL1N.003/2000.02.11/ 
