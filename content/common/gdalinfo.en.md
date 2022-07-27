---
author: ['Jakob Miksch']
date: 1657894221
title: "gdalinfo, TLDR Pages"
description: "gdalinfo, List various information about a GDAL supported raster dataset."
categories: "common"
---
> More information: <https://gdal.org/programs/gdalinfo.html>.

- List all supported raster formats:

```bash
gdalinfo --formats
```

- List information about a specific raster dataset:

```bash
gdalinfo path/to/input.tif
```

- List information about a specific raster dataset in JSON format:

```bash
gdalinfo -json path/to/input.tif
```

- Show histogram values of a specific raster dataset:

```bash
gdalinfo -hist path/to/input.tif
```

- List information about a Web Map Service (WMS):

```bash
gdalinfo WMS:https://services.meggsimum.de/geoserver/ows
```

- List information about a specific dataset of a Web Map Service (WMS):

```bash
gdalinfo WMS:https://services.meggsimum.de/geoserver/ows -sd 4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | gdalinfo: add page (#8162) * gdalinfo: add page * Update pages/common/gdalinfo.md Co-authored-by: Emily Grace Seville [...] | 2022-07-15T16:10:21 | [6415af8d84a0](https://github.com/tldr-pages/tldr/commit/6415af8d84a056876357d9a679e9d161ae2d5e9a)

