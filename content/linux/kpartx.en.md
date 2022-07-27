---
author: ['Lucas Gabriel Schneider', 'sedrubal']
date: 1630607629
title: "kpartx, TLDR Pages"
description: "kpartx, Create device maps from partition tables."
categories: "linux"
---
> More information: <https://manned.org/kpartx>.

- Add partition mappings:

```bash
kpartx -a whole_disk.img
```

- Delete partition mappings:

```bash
kpartx -d whole_disk.img
```

- List partition mappings:

```bash
kpartx -l whole_disk.img
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[sedrubal](mailto:sedrubal@users.noreply.github.com) | kpartx: add page (#2947) | 2019-05-01T17:29:08 | [dbf4e9979682](https://github.com/tldr-pages/tldr/commit/dbf4e997968223ac4772c0634aa044cac0648685)

