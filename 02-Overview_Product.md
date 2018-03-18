# Product Design

## Main features

Listed here generic features according to different layers of activity. Starting vocabulary:
* [Web maps or slippy maps](https://wiki.openstreetmap.org/wiki/Slippy_Map)
* [Global Discrete Tiling System](http://www.maptiler.org/google-maps-coordinates-tile-bounds-projection/): as in every slippy map, 
it is a modern method for subdiving Earth surface into smaller polygons that are well-defined and with a unique id; but only locally uniform in area.
Each polygon is usually defined by a row number, a column number and a zoom level, see [OSM zoom levels](https://wiki.openstreetmap.org/wiki/Zoom_levels).

### User Experience
* Tile-based: user defines an AoI based on tiles of interest
* Pay by metrics: the tupling of tiles (number and size), time intervals (year, season, months) defines the pricing (analitycs and indices can be pre-defined based on the business case)

### Frontend
* Possibility of selecting tiles using Global Discrete Tiling System
* Possiblity of defining a mix of metrics
* ...

### Backend
* Services integration via software-as-a-service (Python toolkits over different providers of data)

### Analytics
* ...

### System, generic design principles
* Google Cloud
* Lambdas
* Semantically Linked Datastore
* Tiles' changes stored as DAG
* "Everything is a graph"
