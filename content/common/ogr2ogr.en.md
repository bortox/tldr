---
author: ['Jakob Miksch']
date: 1647713811
title: "ogr2ogr"
description: "ogr2ogr, Convert geospatial vector data between file formats."
categories: "common"
---
> More information: <https://gdal.org/programs/ogr2ogr.html>.

- Convert a Shapefile into a GeoPackage:

```bash
ogr2ogr -f GPKG path/to/output.gpkg path/to/input.shp
```

- Reduce a GeoJSON to features matching a condition:

```bash
ogr2ogr -where 'myProperty > 42' -f GeoJSON path/to/output.geojson path/to/input.geojson
```

- Change coordinate reference system of a GeoPackage from `EPSG:4326` to `EPSG:3857`:

```bash
ogr2ogr -s_srs EPSG:4326 -t_srs EPSG:3857 -f GPKG path/to/output.gpkg path/to/input.gpkg
```

- Convert a CSV file into a GeoPackage, specifying the names of the coordinate columns and assigning a coordinate reference system:

```bash
ogr2ogr -f GPKG path/to/output.gpkg path/to/input.csv -oo X_POSSIBLE_NAMES=longitude -oo Y_POSSIBLE_NAMES=latitude -a_srs EPSG:4326
```

- Load a GeoPackage into a PostGIS database:

```bash
ogr2ogr -f PostgreSQL PG:dbname="database_name" path/to/input.gpkg
```

- Clip layers of a GeoPackage file to the given bounding box:

```bash
ogr2ogr -spat min_x min_y max_x max_y -f GPKG path/to/output.gpkg path/to/input.gpkg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | ogr2ogr, ogrinfo: refresh (#7904) | 2022-03-19T19:16:51 | [c9cfd040659d](https://github.com/tldr-pages/tldr/commit/c9cfd040659de3f90feee5a289146775343d9b1a)
[Jakob Miksch](mailto:info@jakobmiksch.eu) | ogr2ogr, ogrinfo: refresh (#7807) | 2022-02-27T14:50:07 | [0f73f6aaad48](https://github.com/tldr-pages/tldr/commit/0f73f6aaad48ab1887b5019c948b39a8ab90ac9b)
[Jakob Miksch](mailto:jakob.miksch@posteo.eu) | ogr2ogr, ogrinfo: add pages (#3337) | 2019-10-29T16:36:20 | [ca0861295845](https://github.com/tldr-pages/tldr/commit/ca086129584524895a97f21ac8664030db1fb710)

