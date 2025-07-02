# quick-look-maps
Cylindrical projections of ammonia, cloud pressure, and visual context


Release 1.0 - Initial Release
Quick-look maps of ammonia abundance, cloud pressure, and visual context are provided for the 2022, 2023-24, and 2024-25 apparitions of Jupiter using the band-average average method developed by Hill et al., 2024. The maps are composed of multiple observations spanning no more than a couple of nights of observing, and in 2024-25, often just a single night. Two types of files are provided:

1) Files containing three plots for a single collection of observations - top: ammonia, middle: cloud pressure, bottom: IrGB context. The naming convention is <YYYYMMDD-YYYYMMDD> Mean Sys<rot sys> <Lon1-Lon2> <Lat1-Lat2> map.png, for example: 20230815-20230818 Mean Sys1 0-360 15N-15S map.png.

2) Files containing a stack of maps for a single parameter for the entire apparition, i.e., either ammonia, cloud pressure, or IrGB context. Thus, there are only three files of this type per apparition. The file naming convention is 2023 <NH3/CH4/RGB> Stack Sys<rot sys> <Lon1-Lon2> <Lat1-Lat2> map.png, for example: 2023 NH3 Stack Sys2 0-360 60N-60S map.png, where CH4 represents the cloud pressure.

The directory structure includes paths for two different color tables for the cloud pressure. The /Blue Color Table directory uses a blue-white table to represent cloud height in a way similar to that used in terrestrial meteorology, where white represents clouds higher in the atmosphere. The /Red Color Table directory uses a color table similar to that used for 5-micron observations of Jupiter, where dark areas represent thicker or higher overlying clouds and bright red/orange areas indicate deeper clouds. The ammonia data and context images are rendered the same in each color table directory. 

Within each of the two color table directories are three subdirectories, one for each apparition. The data rendered is the same regardless of the color table. Within each apparition subdirectory are System II maps covering 60N-60S planetographic latitudes and System I maps covering 15N-15S planetographic latitudes. The System I maps facilitate study of hot-spot, plume, and ammonia abundance in the Equatorial Zone (EZ) evolution during an apparition.

NOTE: These are quick-look data and do not necessarily represent final, science grade processing. In addition, only about 70% of the 2024-25 data have been processed into maps. Future updates will include additional data.


Hill, S. M., Irwin, P. G. J., Alexander, C., & Rogers, J. H. (2024). Spatial variations of Jovian tropospheric ammonia via ground‐based imaging. Earth and Space Science, 11, e2024EA003562. https://doi.org/10.1029/2024EA003562
