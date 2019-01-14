# Open street map - drinking water in Sofia

[OpenStreetMap] is built by a community of mappers that contribute and maintain data about roads, trails, cafés, railway stations, and much more, all over the world.

Today we'll be looking at the public drinking water amenities (чешмички) in Sofia dataset.

The goals of this kata are to: 

* parse the XML [data] (don't worry, it's just a list of objects, no crazy recursive hierarchies)
* explore the data (pick the question(s) that are most interesting to you):
    * which node is closest to your home? to your office?
    * how many nodes are wheelchair accessible?
    * how many attributes on average does a node have?
    * what is the most common attribute, besides ```amenity```?
    * how many "types" are needed to represent the data, if the attributes can't be Null?

* have fun





P.S. The data was extracted via [overpass turbo]. 


[OpenStreetMap]: https://www.openstreetmap.org/way/166216724

[data]: https://github.com/lambda-dojo-sofia/open-street-map/blob/master/data/Drinking%20water.osm

[overpass turbo]: https://overpass-turbo.eu/