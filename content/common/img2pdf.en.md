---
author: ['Felipe-noob']
date: 1631909156
title: "img2pdf, TLDR Pages"
description: "img2pdf, Command-line lossless converter of raster images to PDF."
categories: "common"
---
> More information: <https://gitlab.mister-muffin.de/josch/img2pdf>.

- Convert multiple images to a single PDF, each image being on its own page:

```bash
img2pdf path/to/image1.jpg path/to/image2.jpg --output path/to/file.pdf
```

- Convert only the first frame of a multi-frame image to PDF:

```bash
img2pdf path/to/file.gif --first-frame-only --output path/to/file.pdf
```

- Auto orient the image, use a page size of A4 in landscape mode, and set a border of 2cm horizontally and 5.1cm vertically:

```bash
img2pdf path/to/file.jpg --auto-orient --pagesize A4^T --border 2cm:5.1cm --output path/to/file.pdf
```

- Shrink only larger images to a 10cm by 15cm rectangle inside a 30x20cm page:

```bash
img2pdf path/to/file.tiff --pagesize 30cmx20cm --imgsize 10cmx15cm --fit shrink --output path/to/file.pdf
```

- Convert an image to PDF, and specify metadata for the resulting file:

```bash
img2pdf path/to/file.png --title title --author author --creationdate 1970-01-31 --keywords keyword1 keyword2 --subject subject --output path/to/file.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Felipe-noob](mailto:80780954+Felipe-noob@users.noreply.github.com) | img2pdf: add page (#6519) | 2021-09-17T22:05:56 | [39fcb516e4d6](https://github.com/tldr-pages/tldr/commit/39fcb516e4d6e251190397e90d63df40ac2b8627)

