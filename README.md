# GIS-
start with creating resistance raster on GIS (use land cover, streams , elevation, roads) clip file to just see study site of Mexico
clip raster of land cover -windows:image analysis-> zoom and clip raster 
clip all polygons to boundaries of Michoacán, Mexico
turn all polygons to shapefiles-->then to raster 
mosaic to new raster tool (combines all raster layers together into one resistance map)
reclassify protected areas as nodes in chronological order (1,2,3,4......,41)
raster data= export_output_2_polygontoRas (protected areas)
feature_shp1=roads
Feature_shp2=streams
Feature_shp3=outline of border
waterbodies1=waterbodies 
after my raster data was all put together in order to reclassify you right lcik on the layer and go to proterties--> symbology and go to the values and change, then apply and ok.(raster mexico reclassifed file)

maxent: import monarch occurance data csv (MS DOs with comma seperation) into Arcmap 10.2
make an inset map of monarch distrubtion in mexcio-- this is present data 
