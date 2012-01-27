![Tile Previews](https://github.com/nvkelso/geo-how-to/raw/master/images/tile_providers_preview.png)

For a good overview, check out the [Switch2osm](http://switch2osm.org/) site. The tips and tricks here apply to OSM somewhat, but more specifically to BYOD (bring your down data).

## Getting started

* [Software](https://github.com/nvkelso/geo-how-to/wiki/Getting-started:-SOFTWARE) - Install critical software and links to tutorials.

* [Data](https://github.com/nvkelso/geo-how-to/wiki/Getting-started:-DATA) - Download OSM and Natural Earth data.

* [Example workflow](https://github.com/nvkelso/geo-how-to/wiki/Getting-started:-WORKFLOW) - Start a project, import data, export data, create tiles.

* [Web mapping = API + tiles](https://github.com/nvkelso/geo-how-to/wiki/Getting-started:-OVERVIEW) - Slippy maps on the web have two parts: images tiles that make up the map, and an API framework that stitches tiles together and handles interactive panning and zooming.

* [Why go open source geo](https://github.com/nvkelso/geo-how-to/wiki/Why-go-open-source-geo) - Read what the community is saying.

* [Map examples](https://github.com/nvkelso/geo-how-to/wiki/Map-examples) - Pretty basemap tiles and compelling interactive maps.

## Mapping

* [PostGIS](https://github.com/nvkelso/geo-how-to/wiki/PostGIS) - Store your geography in a spatial database (kinda the open source version of an Esri GeoDB). Faster than raw SHP files when speed matters. Storage default for OSM data.

* [OGR, GDAL](https://github.com/nvkelso/geo-how-to/wiki/OGR-to-reproject,-modify-Shapefiles) - Reproject, sort, filter and otherwise modify Shapefiles and other vector map data formats. GDAL for raster. These are amazingly powerful.

* [QGIS](https://github.com/nvkelso/geo-how-to/wiki/QGIS) - The open source alternative to ArcMap, but not as industrial strength. It's a GUI for composing maps and doing simple analysis.

* [Map Styling](https://github.com/nvkelso/geo-how-to/wiki/Map-Styling-in-cascadenik,-carto) - Cascadenik, carto since raw Mapnik XML is hellish.

* [Style Hub](https://github.com/nvkelso/geo-how-to/wiki/Style-Hub) - Pre-baked stylesheets for drawing OSM and Natural Earth data.

* [TileStache](https://github.com/nvkelso/geo-how-to/wiki/TileStache) - Cache web map tiles, from Stamen.

* [Dymo](https://github.com/nvkelso/geo-how-to/wiki/Dymo) - Create beautiful map labels, from Stamen.

* [Geocoding](https://github.com/nvkelso/geo-how-to/wiki/Geocoding) - This is the one hard part about going open source geo.

* [Routing](https://github.com/nvkelso/geo-how-to/wiki/Routing) - tk tk tk

* [Shapely](https://github.com/nvkelso/geo-how-to/wiki/Shapely) - Python library for geometric objects, predicates, and operations without requiring PostGIS.

* [Tiles](https://github.com/nvkelso/geo-how-to/wiki/Tiles) - Once you're done designing your map, you'll have 10s of thousands of tiny image files, hundreds and thousands of megabytes in size. You'll need to post these online.

* [Map scales/zooms, coordinate systems](https://github.com/nvkelso/geo-how-to/wiki/Map-scales---zooms) - Web maps have 20 preset scales, learn these “zoom” levels and their natural scale equivelents.

* [Generalize your data](https://github.com/nvkelso/geo-how-to/wiki/Generalize your data) - Seriously. Your maps will look better and load faster.

* [GeoJSON](https://github.com/nvkelso/geo-how-to/wiki/GeoJSON) - Make it smaller. Giving your data the precision it's accuracy deserves.

* [MaPublisher](https://github.com/nvkelso/geo-how-to/wiki/MaPublisher) - Make maps in Adobe Illustrator.

## Unix command line

* [Makefiles](https://github.com/nvkelso/geo-how-to/wiki/Make-files) - Key to organizing your workflow and making it repeatable.

* [Python](https://github.com/nvkelso/geo-how-to/wiki/Python) - tk tk tk

* [General Unix commands](https://github.com/nvkelso/geo-how-to/wiki/Unix-commands)

* [Download onto server using CURL](https://github.com/nvkelso/geo-how-to/wiki/Download-onto-server-using-CURL)

* [File permissions](https://github.com/nvkelso/geo-how-to/wiki/File-permissions)

* [GREP](https://github.com/nvkelso/geo-how-to/wiki/GREP) - Data formatting problems? Advanced text find-replace to the rescue.

* [SSH keys](https://github.com/nvkelso/geo-how-to/wiki/SSH-keys)

* [ZIP on the server](https://github.com/nvkelso/geo-how-to/wiki/ZIP-on-the-server)

## Project management:

* [Git aka Github](https://github.com/nvkelso/geo-how-to/wiki/Github)

* [SVN aka Subversion](https://github.com/nvkelso/geo-how-to/wiki/SVN-aka-Subversion)

## Other

* [Markdown is the devil](https://github.com/nvkelso/geo-how-to/wiki/Markdown-is-evil) - Yet another random raw text formatting style without a GUI.
