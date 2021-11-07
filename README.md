# boulder_trailheads_parks
Trailheads in relation to public parks in Boulder County Colorado

## TOC
- [Data:](#Data:)

## Data:
 2021 TIGER/Line Shapefiles
 [Boulder County Colorado](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2021&layergroup=County+Subdivisions): downloaded as shapefile, opened in QGIS (version 3.16) filtered for Boulder County CO and exported as geoJSON.  

[Boulder Area Trailheads of Boulder County](https://opendata-bouldercounty.hub.arcgis.com/datasets/bouldercounty::boulder-area-trailheads/about):
downloaded as geoJSON from Boulder Open Data Portal. ([Metadata](https://www.arcgis.com/sharing/rest/content/items/3a950053bbef46c6a3c2abe3aceee3de/info/metadata/metadata.xml?format=default&output=html))  

Public Leisure Parks: Used QGIS (version 3.16) QuickOSM plugin (version 1.14.3) to pull Key: leisure Value: park from OpenStreetMaps within the area of Boulder County Colorado. Exported from QGIS as [geoJSON](data/boulder_co_trailheads_wgs84.geojson)



