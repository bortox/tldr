---
author: ['Jakob Miksch']
date: 1659352395
title: "gdal_translate"
description: "gdal_translate, Convert raster data between different formats."
categories: "common"
---
> More information: <https://gdal.org/programs/gdal_translate>.

- Convert a raster dataset to JPEG format:

```bash
gdal_translate -of JPEG path/to/input.tif path/to/output.jpeg
```

- Assign a projection to a raster dataset:

```bash
gdal_translate -a_srs EPSG:4326 path/to/input.tif path/to/output.tif
```

- Reduce the size of a raster dataset to a specific fraction:

```bash
gdal_translate -outsize 40% 40% path/to/input.tif path/to/output.tif
```

- Convert a GeoTiff to a Cloud Optimized GeoTiff:

```bash
gdal_translate path/to/input.tif path/to/output.tif -of COG -co COMPRESS=LZW
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | gdal_translate: add page (#8272) | 2022-08-01T13:13:15 | [6ab6eb95dec0](https://github.com/tldr-pages/tldr/commit/6ab6eb95dec010518bbcd45c06a658b4fea14a91)

