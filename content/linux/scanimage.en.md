---
author: ['Dian Fay']
date: 1573618490
title: "scanimage, TLDR Pages"
description: "scanimage, Scan images with the Scanner Access Now Easy API."
categories: "linux"
---
> More information: <http://sane-project.org/man/scanimage.1.html>.

- List available scanners to ensure the target device is connected and recognized:

```bash
scanimage -L
```

- Scan an image and save it to a file:

```bash
scanimage --format=pnm|tiff|png|jpeg > path/to/new_image
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dian Fay](mailto:dmfay@users.noreply.github.com) | scanimage: add page (#3543) | 2019-11-13T05:14:50 | [096883aa4603](https://github.com/tldr-pages/tldr/commit/096883aa4603540993ea948f4c219a19c749765e)

