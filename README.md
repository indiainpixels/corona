Draw a map of India with [D3.js](https://github.com/d3), [Topojson](https://github.com/mbostock/topojson), and five simple functions:

- `centerZoom` - Automatically centers and scales your map to its container, and returns your map's outer boundaries in case you want to draw them.
- `drawOuterBoundary` - Uses the boundary returned from `centerZoom` to draw a boundary around your whole map.
- `drawPlaces` - Draws place names, if your topojson has places.
- `drawSubunits` - Draws subunits.
- `colorSubunits` - Colors the subunits.

This map uses a [Mercator projection](https://en.wikipedia.org/wiki/Mercator_projection), and the colors are generated from [`d3.schemeCategory20`](https://github.com/d3/d3-scale/blob/master/README.md#schemeCategory20). For a tutorial on converting Geojson to Topojson and for finding the coordinates of major cities, see [this tutorial](https://bost.ocks.org/mike/map/).