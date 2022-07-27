---
author: ['Jakob Miksch']
date: 1656332892
title: "gdal2tiles.py, TLDR Pages"
description: "gdal2tiles.py, Generate TMS or XYZ tiles for a raster dataset."
categories: "common"
---
> More information: <https://gdal.org/programs/gdal2tiles.html>.

- Generate TMS tiles for the zoom levels 2-5 of a raster dataset:

```bash
gdal2tiles.py --zoom=2-5 path/to/input.tif path/to/output_directory
```

- Generate XYZ tiles for the zoom levels 2-5 of a raster dataset:

```bash
gdal2tiles.py --zoom=2-5 --xyz path/to/input.tif path/to/output_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | gdal2tiles.py: add page (#8156) | 2022-06-27T14:28:12 | [c9654d05b797](https://github.com/tldr-pages/tldr/commit/c9654d05b797dce4c0fec705acc8be47707c5536)

