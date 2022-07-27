---
author: ['CleanMachine1', 'Samuel Woon']
date: 1624920504
title: "tune2fs, TLDR Pages"
description: "tune2fs, Adjust parameters of an ext2, ext3 or ext4 filesystem."
categories: "linux"
---
> May be used on mounted filesystems.

> More information: <https://manned.org/tune2fs>.

- Set the max number of counts before a filesystem is checked to 2:

```bash
tune2fs -c 2 /dev/sdXN
```

- Set the filesystem label to MY_LABEL:

```bash
tune2fs -L 'MY_LABEL' /dev/sdXN
```

- Enable discard and user-specified extended attributes for a filesystem:

```bash
tune2fs -o discard,user_xattr /dev/sdXN
```

- Enable journaling for a filesystem:

```bash
tune2fs -o^nobarrier /dev/sdXN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/t*: add information link (#6166) | 2021-06-29T00:48:24 | [d86d3d6206bd](https://github.com/tldr-pages/tldr/commit/d86d3d6206bdf76257ce480be4a8a71d2d4fdda6)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | tune2fs: add page (#4297) | 2020-09-05T13:42:27 | [7229778c1d34](https://github.com/tldr-pages/tldr/commit/7229778c1d3465ed820bf646444487fce187145c)

