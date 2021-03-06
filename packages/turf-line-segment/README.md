# @turf/line-segment

# lineSegment

Creates a [FeatureCollection](http://geojson.org/geojson-spec.html#feature-collection-objects) of 2-vertex [LineString](http://geojson.org/geojson-spec.html#linestring) segments from a [(Multi)LineString](http://geojson.org/geojson-spec.html#linestring) or [(Multi)Polygon](http://geojson.org/geojson-spec.html#polygon).

**Parameters**

-   `geojson` **([Geometry](http://geojson.org/geojson-spec.html#geometry) \| [FeatureCollection](http://geojson.org/geojson-spec.html#feature-collection-objects) \| [Feature](http://geojson.org/geojson-spec.html#feature-objects)&lt;([LineString](http://geojson.org/geojson-spec.html#linestring) \| [MultiLineString](http://geojson.org/geojson-spec.html#multilinestring) \| [MultiPolygon](http://geojson.org/geojson-spec.html#multipolygon) \| [Polygon](http://geojson.org/geojson-spec.html#polygon))>)** GeoJSON Polygon or LineString

**Examples**

```javascript
var polygon = turf.polygon([[[-50, 5], [-40, -10], [-50, -10], [-40, 5], [-50, 5]]]);
var segments = turf.lineSegment(polygon);

//addToMap
var addToMap = [polygon, segments]
```

Returns **[FeatureCollection](http://geojson.org/geojson-spec.html#feature-collection-objects)&lt;[LineString](http://geojson.org/geojson-spec.html#linestring)>** 2-vertex line segments

<!-- This file is automatically generated. Please don't edit it directly:
if you find an error, edit the source file (likely index.js), and re-run
./scripts/generate-readmes in the turf project. -->

---

This module is part of the [Turfjs project](http://turfjs.org/), an open source
module collection dedicated to geographic algorithms. It is maintained in the
[Turfjs/turf](https://github.com/Turfjs/turf) repository, where you can create
PRs and issues.

### Installation

Install this module individually:

```sh
$ npm install @turf/line-segment
```

Or install the Turf module that includes it as a function:

```sh
$ npm install @turf/turf
```
