---
author: ['Axel Navarro']
date: 1642532135
title: "avifenc, TLDR Pages"
description: "avifenc, AV1 Image File Format (AVIF) encoder."
categories: "linux"
---
> More information: <https://aomediacodec.github.io/av1-avif/>.

- Convert a specific PNG image to AVIF:

```bash
avifenc path/to/image.png path/to/image.avif
```

- Encode with a specific speed, where 0=slowest, 10=fastest, and 6=default:

```bash
avifenc --speed 2 path/to/image.png path/to/image.avif
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | avifenc: add page (#7636) | 2022-01-18T19:55:35 | [3b4aecafb84e](https://github.com/tldr-pages/tldr/commit/3b4aecafb84e3a8fd9007ead470c7f911fd6550a)

