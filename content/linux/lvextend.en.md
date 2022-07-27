---
author: ['Adam Herst', 'Samuel Woon', 'Seth Falco', 'bl-ue']
date: 1629050349
title: "lvextend, TLDR Pages"
description: "lvextend, Increase the size of a logical volume."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/lvextend.8.html>.

- Increase a volume's size to 120 GB:

```bash
lvextend --size 120G logical_volume
```

- Increase a volume's size by 40 GB as well as the underlying filesystem:

```bash
lvextend --size +40G -r logical_volume
```

- Increase a volume's size to 100% of the free physical volume space:

```bash
lvextend --size 100%FREE logical_volume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Adam Herst](mailto:adamherst@adamherst.com) | lvextend: expand description (#5311) | 2021-02-26T11:44:19 | [a57cc1478316](https://github.com/tldr-pages/tldr/commit/a57cc14783160e77e20ddfd9f04dcabdb902e8d9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Samuel Woon](mailto:samuel.woon@protonmail.com) | lvextend, lvreduce, lvresize: add page (#4239) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-08-10T13:03:18 | [6310c0897540](https://github.com/tldr-pages/tldr/commit/6310c0897540f0ed5769e2589c25165eae9ba359)

