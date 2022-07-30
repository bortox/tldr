---
author: ['Lucas Gabriel Schneider', 'John Curcio']
date: 1629110041
title: "mkfs"
description: "mkfs, Build a Linux filesystem on a hard disk partition."
categories: "linux"
---
> This command is deprecated in favor of filesystem specific mkfs.<type> utils.

> More information: <https://manned.org/mkfs>.

- Build a Linux ext2 filesystem on a partition:

```bash
mkfs path/to/partition
```

- Build a filesystem of a specified type:

```bash
mkfs -t ext4 path/to/partition
```

- Build a filesystem of a specified type and check for bad blocks:

```bash
mkfs -c -t ntfs path/to/partition
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[John Curcio](mailto:john@curcio.dev) | mkfs: add page (#3284) | 2019-10-02T18:06:35 | [dc7c28a5d55c](https://github.com/tldr-pages/tldr/commit/dc7c28a5d55c74c0d3b97591d89d6e3510fab8a2)

