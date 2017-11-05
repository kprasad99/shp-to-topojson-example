# shp-to-topojson-example
Steps to convert Geo SHP file to Topojson

## 1. Install Shape to GeoJSON converter plugin.

```
npm install -g shapefile

```

## 2. Convert Shape to GeoJSON file.

```
shp2json  example/indea.states.shp -o india.states.geojson

```

## 3. Install Topojson plugin.

```
npm install topojson topojson-client -g

```

## 4. Convert GeoJSON to TopoJSON file.

```
geo2topo india.states.geojson -o india.states.topojson

```
