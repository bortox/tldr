---
author: ['tassadarliu']
date: 1614532319
title: "pngcheck, TLDR Pages"
description: "pngcheck, Print detailed information about and verify PNG, JNG, and MNG files."
categories: "common"
---
> More information: <http://www.libpng.org/pub/png/apps/pngcheck.html>.

- Print a summary for an image (width, height, and color depth):

```bash
pngcheck image.png
```

- Print information for an image with [c]olorized output:

```bash
pngcheck -c image.png
```

- Print [v]erbose information for an image:

```bash
pngcheck -cvt image.png
```

- Receive an image from stdin and display detailed information:

```bash
cat path/to/image.png | pngcheck -cvt
```

- [s]earch for PNGs within a specific file and display information about them:

```bash
pngcheck -s image.png
```

- Search for PNGs within another file and e[x]tract them:

```bash
pngcheck -x image.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[tassadarliu](mailto:rhapsodyn@gmail.com) | pngcheck: add page (#5310) | 2021-02-28T18:11:59 | [ad2fd7c87e4d](https://github.com/tldr-pages/tldr/commit/ad2fd7c87e4d2b17fe3f3d0a462cc11483d900e6)

