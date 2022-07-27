---
author: ['Marco Bonelli', 'Martin Juul', 'Emily Grace Seville']
date: 1644837703
title: "sips, TLDR Pages"
description: "sips, Apple Scriptable Image Processing System."
categories: "osx"
---
> Raster/Query images and ColorSync ICC Profiles.

> More information: <https://ss64.com/osx/sips.html>.

- Specify an output directory so that originals do not get modified:

```bash
sips --out path/to/out_dir
```

- Resample image at specified size, Image aspect ratio may be altered:

```bash
sips --resampleHeightWidth 1920 300 image.ext
```

- Resample image so height and width aren't greater than specified size (notice the capital Z):

```bash
sips --resampleHeightWidthMax 1920 300 image.ext
```

- Resample all images in a directory to fit a width of 960px (honoring aspect ratio):

```bash
sips --resampleWidth 960 path/to/images
```

- Convert an image from CMYK to RGB:

```bash
sips --matchTo "/System/Library/ColorSync/Profiles/Generic RGB Profile.icc" path/to/image.ext path/to/out_dir
```

- Remove ColorSync ICC profile from an image:

```bash
sips --deleteProperty profile --deleteColorManagementProperties path/to/image.ext
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Martin Juul](mailto:11337105+martin-juul@users.noreply.github.com) | sips: add page (#2033) | 2018-03-23T09:52:50 | [8c8f832abb74](https://github.com/tldr-pages/tldr/commit/8c8f832abb7406255ce03bc776bf07891d08c3e2)

