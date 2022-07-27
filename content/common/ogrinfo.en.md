---
author: ['Jakob Miksch']
date: 1647713811
title: "ogrinfo, TLDR Pages"
description: "ogrinfo, List information about an OGR-supported data source."
categories: "common"
---
> More information: <https://gdal.org/programs/ogrinfo.html>.

- List supported formats:

```bash
ogrinfo --formats
```

- List layers of a data source:

```bash
ogrinfo path/to/input.gpkg
```

- Get detailed information about a specific layer of a data source:

```bash
ogrinfo path/to/input.gpkg layer_name
```

- Show summary information about a specific layer of a data source:

```bash
ogrinfo -so path/to/input.gpkg layer_name
```

- Show summary of all layers of the data source:

```bash
ogrinfo -so -al path/to/input.gpkg
```

- Show detailed information of features matching a condition:

```bash
ogrinfo -where 'attribute_name > 42' path/to/input.gpkg layer_name
```

- Update a layer in the data source with SQL:

```bash
ogrinfo path/to/input.geojson -dialect SQLite -sql "UPDATE input SET attribute_name = 'foo'"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | ogr2ogr, ogrinfo: refresh (#7904) | 2022-03-19T19:16:51 | [c9cfd040659d](https://github.com/tldr-pages/tldr/commit/c9cfd040659de3f90feee5a289146775343d9b1a)
[Jakob Miksch](mailto:info@jakobmiksch.eu) | ogr2ogr, ogrinfo: refresh (#7807) | 2022-02-27T14:50:07 | [0f73f6aaad48](https://github.com/tldr-pages/tldr/commit/0f73f6aaad48ab1887b5019c948b39a8ab90ac9b)
[Jakob Miksch](mailto:jakob.miksch@posteo.eu) | ogr2ogr, ogrinfo: add pages (#3337) | 2019-10-29T16:36:20 | [ca0861295845](https://github.com/tldr-pages/tldr/commit/ca086129584524895a97f21ac8664030db1fb710)

