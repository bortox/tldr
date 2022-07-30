---
author: ['85pando', 'Lucas Gabriel Schneider', 'João Pedro Fonseca Dantas']
date: 1629110041
title: "mke2fs"
description: "mke2fs, Creates a Linux filesystem inside a partition."
categories: "linux"
---
> More information: <https://manned.org/mke2fs>.

- Create an ext2 filesystem in partition 1 of device b (`sdb1`):

```bash
mkfs.ext2 /dev/sdb1
```

- Create an ext3 filesystem in partition 1 of device b (`sdb1`):

```bash
mkfs.ext3 /dev/sdb1
```

- Create an ext4 filesystem in partition 1 of device b (`sdb1`):

```bash
mkfs.ext4 /dev/sdb1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[João Pedro Fonseca Dantas](mailto:67479090+jopefd@users.noreply.github.com) | mke2fs: replace ext3 duplicaded for new ext4 (#6054) | 2021-05-27T18:17:46 | [3b84ce570f69](https://github.com/tldr-pages/tldr/commit/3b84ce570f694df9bdde547b4ff6fed174c6ac1d)
[85pando](mailto:85pando@googlemail.com) | Add several mkfs tools | 2016-01-13T16:50:06 | [7521d8b8930e](https://github.com/tldr-pages/tldr/commit/7521d8b8930e629d0a2d7a9e15b1eab704c2ebc8)

