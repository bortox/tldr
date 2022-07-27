---
author: ['Jakob Miksch']
date: 1647714416
title: "ogrmerge.py, TLDR Pages"
description: "ogrmerge.py, Merge several vector datasets into a single one."
categories: "common"
---
> More information: <https://gdal.org/programs/ogrmerge.html>.

- Create a GeoPackage with a layer for each input Shapefile:

```bash
ogrmerge.py -f GPKG -o path/to/output.gpkg path/to/input1.shp path/to/input2.shp ...
```

- Create a virtual datasource (VRT) with a layer for each input GeoJSON:

```bash
ogrmerge.py -f VRT -o path/to/output.vrt path/to/input1.geojson path/to/input2.geojson ...
```

- Concatenate two vector datasets and store source name of dataset in attribute 'source_name':

```bash
ogrmerge.py -single -f GeoJSON -o path/to/output.geojson -src_layer_field_name country source_name path/to/input1.shp path/to/input2.shp ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | ogrmerge.py: add page (#7903) | 2022-03-19T19:26:56 | [00e01e07ac6b](https://github.com/tldr-pages/tldr/commit/00e01e07ac6bb465f3db69f58beb665373591d73)

