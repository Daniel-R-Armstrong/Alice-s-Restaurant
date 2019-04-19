

## Raster Data 
I picture it as a grid system were each in the grid  were the color represents an aspect of intrest, like land use. 
bigger files but faster graphic rendering. 
> ### Raster File Formats:
> TIFF-
> JPEG-
GDAL (Geospatial Data Abstraction Library) is the open source Swiss Army knife of raster formats. It also includes the OGR simple features library for vector formats.

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

### working with lines
#### Lines dont meet
- Snap Noncontiguous Line Features [source](http://andrewgaidus.com/Shapely_Geometries_Topological_Rules/)
- Identify the distance between the end points of two line segments [source](http://andrewgaidus.com/Shapely_Geometries_Topological_Rules/)
- snap line segments within end point threshold distance [source](http://andrewgaidus.com/Shapely_Geometries_Topological_Rules/)
- Make Line Feature end at Polygon Boundaries [source](http://andrewgaidus.com/Shapely_Geometries_Topological_Rules/)
_ Extending lines [source](http://andrewgaidus.com/Shapely_Geometries_Topological_Rules/)
- Cliping lines [source](http://andrewgaidus.com/Shapely_Geometries_Topological_Rules/)

### Tools/api
https://www.mapzen.com/products/  
 Map display, Search, Autocomplete, Turn-by-Turn, Isochrone, Map Matching, Optimized Route, Time-distance Matrix, Mobile, Pricing
 
 https://open-elevation.com/
 
 ### Notebooks
 [PostGIS_Database](https://github.com/agaidus/PostgreSQL_PostGIS_Databases_Python/blob/master/Build_Query_Spatial_Database.ipynb)
 
 [elevation of drive](https://github.com/agaidus/SF_Muni_Elevation)
 
 
 [census block projections](https://github.com/agaidus/Build_Reaggregate_Geography_Demographics)
