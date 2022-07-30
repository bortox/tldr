---
author: ['Alex', 'Seth Falco']
date: 1629050349
title: "zsteg"
description: "zsteg, Steganography detection tool for PNG and BMP file formats."
categories: "common"
---
> It detects LSB steganography, ZLIB-compressed data, OpenStego, Camouflage and LSB with the Eratosthenes set.

> More information: <https://github.com/zed-0xff/zsteg>.

- Detect embedded data in a PNG:

```bash
zsteg path/to/image.png
```

- Detect embedded data in a BMP image, using all known methods:

```bash
zsteg --all path/to/image.bmp
```

- Detect embedded data in a PNG, iterating pixels vertically and using MSB first:

```bash
zsteg --msb --order yx path/to/image.png
```

- Detect embedded data in a BMP image, specifying the bits to consider:

```bash
zsteg --bits 1,2,3|1-3 path/to/image.bmp
```

- Detect embedded data in a PNG, extracting only prime pixels and inverting bits:

```bash
zsteg --prime --invert path/to/image.png
```

- Detect embedded data in a BMP image, specifying the minimum length of the strings to be found and the find mode:

```bash
zsteg --min-str-len 10 --strings first|all|longest|none path/to/image.bmp
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Alex](mailto:alexandre.dhondt@gmail.com) | zsteg: add page (#3959) | 2020-04-03T12:00:00 | [aa809e1e2d43](https://github.com/tldr-pages/tldr/commit/aa809e1e2d43f8c78a6b74078d638f8b3863f753)

