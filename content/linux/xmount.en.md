---
author: ['Fake4d']
date: 1623963968
title: "xmount"
description: "xmount, Convert on-the-fly between multiple input and output hard disk image types with optional write cache support."
categories: "linux"
---
> Creates a virtual file system using FUSE (Filesystem in Userspace) that contains a virtual representation of the input image.

> More information: <https://manned.org/xmount>.

- Mount a `.raw` image file into a DMG container file:

```bash
xmount --in raw path/to/image.dd --out dmg mountpoint
```

- Mount an EWF image file with write-cache support into a VHD file to boot from:

```bash
xmount --cache path/to/cache.ovl --in ewf path/to/image.E?? --out vhd mountpoint
```

- Mount the first partition at sector 2048 into a new `.raw` image file:

```bash
xmount --offset 2048 --in raw path/to/image.dd --out raw mountpoint
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fake4d](mailto:Fake4d@users.noreply.github.com) | xmount: add page (#6106) | 2021-06-17T23:06:08 | [c327bf7e7538](https://github.com/tldr-pages/tldr/commit/c327bf7e75380b314f8fa9606b6bf27ef2901135)

