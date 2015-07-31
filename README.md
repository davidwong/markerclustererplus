# MarkerClustererPlus

This is git port of the markerclustererplus library from [google-maps-utility-library-v3](http://google-maps-utility-library-v3.googlecode.com/svn/trunk/markerclustererplus/).

## Changes

Changes from the imported version 2.1.2.

### v0.1

* minClusterZoom option: sets the minimum number of markers in the cluster that will stop further zooming when the cluster is clicked.

### v0.1.1

* divClassName option: when set will add a class name for the div that holds the cluster icon. Currently this is only used as a tag for e2e testing, e.g. to allow selenium to find the clusters in a map.

### v0.2

* workaround for cluster not zooming when clicked, after fitBounds() is called.

## Build

To build a minified version of the library using uglify:
(requires node.js)

```bash
$ npm install
$ npm run build
```

### License

[Apache License, Version 2.0](http://opensource.org/licenses/Apache-2.0)
