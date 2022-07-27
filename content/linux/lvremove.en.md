---
author: ['Adam Herst', 'tkiatd']
date: 1615231512
title: "lvremove, TLDR Pages"
description: "lvremove, Remove one or more logical volumes."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/lvremove.8.html>.

- Remove a logical volume in a volume group:

```bash
sudo lvremove volume_group/logical_volume
```

- Remove all logical volumes in a volume group:

```bash
sudo lvremove volume_group
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[tkiatd](mailto:tkiatd@outlook.com) | lvremove: add page (#4525) | 2020-10-07T22:33:22 | [9149505cb019](https://github.com/tldr-pages/tldr/commit/9149505cb01980ac8036760713cf15fca91dfa3d)

