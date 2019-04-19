

## Raster Data 
I picture it as a grid system were each in the grid  were the color represents an aspect of intrest, like land use. 
bigger files but faster graphic rendering. 
> ### Raster File Formats:
> TIFF-
> JPEG-

## Vector Data

> ### Points
> zero-dimensional points are for single point reference(location), point to "_______" on a map. 

> ### Lines
> One-dimensional lines are used for linear features like roads, topographic lines, rivers, and railroads.
> Line features can measure distance.

> ### Polygons
> Two-dimensional polygons are used for features that cover area, like lakes, census tracks, zoneing, ect.
> Polygon features can measure perimeter and area.

> ### Vector File Formats
> Shapefile – developed by Esri (includes different files which all have to be used todeather)
> GeoJSON – based on JSON
> TIGER – Topologically Integrated Geographic Encoding and Referencing
> GBD - GeoDataBase ()

## Graph Data

> ### NetworkX
> ### Neo4J

## GEO-Data-Bases
> PostgreSQL -PostGIS
> Redis - with the Geo API
> CouchDB - Geocouch

## Concepts
> ### R-tree:
> Preferred method for indexing spatial data. Objects (points, lines, polygons) are grouped and added using the minimum
> bounding rectangle (MBR). They are added in a way that would lead to the smallest increase in size.  

## unverified
Geopandas uses Fiona to read, write, and project spatial data and Shapely to analyze / manipulate it [source](http://andrewgaidus.com/Shapely_Geometries_Topological_Rules/)
