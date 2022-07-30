---
author: ['MT', 'Seth Falco']
date: 1629050349
title: "pdftocairo"
description: "pdftocairo, Converts PDF files to PNG/JPEG/TIFF/PDF/PS/EPS/SVG using cairo."
categories: "common"
---
> More information: <https://poppler.freedesktop.org>.

- Convert a PDF file to JPEG:

```bash
pdftocairo path/to/file.pdf -jpeg
```

- Convert to PDF expanding the output to fill the paper:

```bash
pdftocairo path/to/file.pdf output.pdf -pdf -expand
```

- Convert to SVG specifying the first/last page to convert:

```bash
pdftocairo path/to/file.pdf output.svg -svg -f first_page -l last_page
```

- Convert to PNG with 200ppi resolution:

```bash
pdftocairo path/to/file.pdf output.png -png -r 200
```

- Convert to grayscale TIFF setting paper size to A3:

```bash
pdftocairo path/to/file.pdf -tiff -gray -paper A3
```

- Convert to PNG cropping x and y pixels from the top-left corner:

```bash
pdftocairo path/to/file.pdf -png -x x_pixels -y y_pixels
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[MT](mailto:59728838+mt-empty@users.noreply.github.com) | pdftocairo: add page (#3824) | 2020-02-03T18:54:00 | [131afc3ee1aa](https://github.com/tldr-pages/tldr/commit/131afc3ee1aa5b4a9ae48fe06f3c7d05928e3d7b)

