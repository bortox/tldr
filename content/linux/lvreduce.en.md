---
author: ['Adam Herst', 'Samuel Woon', 'Seth Falco']
date: 1629050349
title: "lvreduce, TLDR Pages"
description: "lvreduce, Reduce the size of a logical volume."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/lvreduce.8.html>.

- Reduce a volume's size to 120 GB:

```bash
lvreduce --size 120G logical_volume
```

- Reduce a volume's size by 40 GB as well as the underlying filesystem:

```bash
lvreduce --size -40G -r logical_volume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | lvextend, lvreduce, lvresize: add page (#4239) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-08-10T13:03:18 | [6310c0897540](https://github.com/tldr-pages/tldr/commit/6310c0897540f0ed5769e2589c25165eae9ba359)

