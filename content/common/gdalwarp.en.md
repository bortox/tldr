---
author: ['Jakob Miksch']
date: 1659447227
title: "gdalwarp"
description: "gdalwarp, Image reprojection and warping utility."
categories: "common"
---
> More information: <https://gdal.org/programs/gdalwarp>.

- Reproject a raster dataset:

```bash
gdalwarp -t_srs EPSG:4326 path/to/input.tif path/to/output.tif
```

- Crop a raster dataset by using specific coordinates:

```bash
gdalwarp -te min_x min_y max_x max_y -te_srs EPSG:4326 path/to/input.tif path/to/output.tif
```

- Crop a raster dataset using a vector layer:

```bash
gdalwarp -cutline path/to/area_to_cut.geojson -crop_to_cutline path/to/input.tif path/to/output.tif
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | gdalwarp: add page (#8274) | 2022-08-02T15:33:47 | [36da1e723fec](https://github.com/tldr-pages/tldr/commit/36da1e723fecb045e4f546d9d18148f6b20dc74c)

