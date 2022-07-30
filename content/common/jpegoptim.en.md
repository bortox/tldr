---
author: ['Samuele', 'pxgamer', 'Starbeamrainbowlabs']
date: 1559788968
title: "jpegoptim"
description: "jpegoptim, Optimise JPEG images."
categories: "common"
---
> More information: <https://github.com/tjko/jpegoptim>.

- Optimise a set of JPEG images, retaining all associated data:

```bash
jpegoptim image1.jpeg image2.jpeg imageN.jpeg
```

- Optimise JPEG images, stripping all non-essential data:

```bash
jpegoptim --strip-all image1.jpeg image2.jpeg imageN.jpeg
```

- Force the output images to be progressive:

```bash
jpegoptim --all-progressive image1.jpeg image2.jpeg imageN.jpeg
```

- Force the output images to have a fixed maximum filesize:

```bash
jpegoptim --size=250k image1.jpeg image2.jpeg imageN.jpeg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | jpegoptim: add link to homepage | 2019-06-06T04:42:48 | [1eef4eec153d](https://github.com/tldr-pages/tldr/commit/1eef4eec153dbb1583c787f534a02ecc49692476)
[Samuele](mailto:samuele@nutellino.it) | jpegoptim: added max size param example (#2301) | 2018-09-11T10:06:44 | [fecba2cd702a](https://github.com/tldr-pages/tldr/commit/fecba2cd702a2d77088d07a7af782c9edf6023c1)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | jpegoptim: add page (#1370) * New command: jpegoptim * Update jpegoptim.md | 2017-05-10T21:46:18 | [c0616697ed57](https://github.com/tldr-pages/tldr/commit/c0616697ed57b22e625b71edd829e5d8834cf730)

