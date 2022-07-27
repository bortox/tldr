---
author: ['ev-john', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "jpegtran, TLDR Pages"
description: "jpegtran, Perform lossless transformation of JPEG files."
categories: "linux"
---
> More information: <https://manned.org/jpegtran>.

- Mirror an image horizontally or vertically:

```bash
jpegtran -flip horizontal|vertical path/to/image.jpg > path/to/output.jpg
```

- Rotate an image 90, 180 or 270 degrees clockwise:

```bash
jpegtran -rotate 90|180|270 path/to/image.jpg > path/to/output.jpg
```

- Transpose the image across the upper-left to lower right axis:

```bash
jpegtran -transpose path/to/image.jpg > path/to/output.jpg
```

- Transverse the image across the upper right to lower left axis:

```bash
jpegtran -transverse path/to/image.jpg > path/to/output.jpg
```

- Convert the image to grayscale:

```bash
jpegtran -grayscale path/to/image.jpg > path/to/output.jpg
```

- Crop the image to a rectangular region of width `W` and height `H` from the upper-left corner, saving the output to a specific file:

```bash
jpegtran -crop WxH -outfile path/to/output.jpg path/to/image.jpg
```

- Crop the image to a rectangular region of width `W` and height `H`, starting at point `X` and `Y` from the upper-left corner:

```bash
jpegtran -crop WxH+X+Y path/to/image.jpg > path/to/output.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[ev-john](mailto:56849582+ev-john@users.noreply.github.com) | jpegtran: add page (#4695) | 2020-10-16T11:14:46 | [6ae53a789f5d](https://github.com/tldr-pages/tldr/commit/6ae53a789f5d8c3563656f44f3ecbb044df9e05f)

