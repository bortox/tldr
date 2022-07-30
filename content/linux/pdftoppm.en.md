---
author: ['Olga']
date: 1644590794
title: "pdftoppm"
description: "pdftoppm, Convert PDF document pages to portable Pixmap (image formats)."
categories: "linux"
---
> More information: <https://manned.org/pdftoppm>.

- Specify the range of pages to convert (N-first page, M-last page):

```bash
pdftoppm -f N -l M path/to/file.pdf image_name_prefix
```

- Convert only the first page of a PDF:

```bash
pdftoppm -singlefile path/to/file.pdf image_name_prefix
```

- Generate a monochrome PBM file (instead of a color PPM file):

```bash
pdftoppm -mono path/to/file.pdf image_name_prefix
```

- Generate a grayscale PGM file (instead of a color PPM file):

```bash
pdftoppm -gray path/to/file.pdf image_name_prefix
```

- Generate a PNG file instead a PPM file:

```bash
pdftoppm -png path/to/file.pdf image_name_prefix
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Olga](mailto:41551585+olgashi@users.noreply.github.com) | pdftoppm: add page (#7764) | 2022-02-11T15:46:34 | [b816d6d8505d](https://github.com/tldr-pages/tldr/commit/b816d6d8505d1dda1a75affdca47509cf8c32a48)

