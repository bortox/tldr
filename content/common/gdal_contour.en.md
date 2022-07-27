---
author: ['Jakob Miksch']
date: 1658730654
title: "gdal_contour, TLDR Pages"
description: "gdal_contour, Create contour lines and polygons from a digital elevation model."
categories: "common"
---
> More information: <https://gdal.org/programs/gdal_contour.html>.

- Create a vector dataset with contour lines spread over an 100-meter [i]nterval while [a]ttributing the elevation property as "ele":

```bash
gdal_contour -a ele -i 100.0 path/to/input.tif path/to/output.gpkg
```

- Create a vector dataset with [p]olygons spread over an 100-meter [i]nterval:

```bash
gdal_contour -i 100.0 -p path/to/input.tif path/to/output.gpkg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jakob Miksch](mailto:info@jakobmiksch.eu) | gdal_contour: add page (#8200) * gdal_contour: add page * Apply suggestions from code review Co-authored-by: Reinhart Previano [...] | 2022-07-25T08:30:54 | [5c490a50e802](https://github.com/tldr-pages/tldr/commit/5c490a50e802496d9b917d61a1fa68e1a30154c2)

