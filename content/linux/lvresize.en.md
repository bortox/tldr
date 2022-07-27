---
author: ['Seth Falco', 'Adam Herst', 'aaaawwWWWwwwwWWW', 'Samuel Woon', 'bl-ue']
date: 1629050349
title: "lvresize, TLDR Pages"
description: "lvresize, Change the size of a logical volume."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/lvresize.8.html>.

- Change the size of a logical volume to 120 GB:

```bash
lvresize --size 120G volume_group/logical_volume
```

- Extend the size of a logical volume as well as the underlying filesystem by 120 GB:

```bash
lvresize --size +120G --resizefs volume_group/logical_volume
```

- Extend the size of a logical volume to 100% of the free physical volume space:

```bash
lvresize --size 100%FREE volume_group/logical_volume
```

- Reduce the size of a logical volume as well as the underlying filesystem by 120 GB:

```bash
lvresize --size -120G --resizefs volume_group/logical_volume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[aaaawwWWWwwwwWWW](mailto:73749744+aaaawwWWWwwwwWWW@users.noreply.github.com) | lvresize: add vg to positional arg and example extend (#5150) | 2021-01-17T19:00:02 | [bd9e5c8630e0](https://github.com/tldr-pages/tldr/commit/bd9e5c8630e0e78504d6eeff588d03cb7287ea0f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | lvextend, lvreduce, lvresize: add page (#4239) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-08-10T13:03:18 | [6310c0897540](https://github.com/tldr-pages/tldr/commit/6310c0897540f0ed5769e2589c25165eae9ba359)

