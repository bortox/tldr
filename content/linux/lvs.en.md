---
author: ['Adam Herst', 'Sahil Dhiman']
date: 1615231512
title: "lvs, TLDR Pages"
description: "lvs, Display information about logical volumes."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/lvs.8.html>.

- Display information about logical volumes:

```bash
lvs
```

- Display all logical volumes:

```bash
lvs -a
```

- Change default display to show more details:

```bash
lvs -v
```

- Display only specific fields:

```bash
lvs -o field_name_1,field_name_2
```

- Append field to default display:

```bash
lvs -o +field_name
```

- Suppress heading line:

```bash
lvs --noheadings
```

- Use a separator to separate fields:

```bash
lvs --separator =
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | lvcreate, lvextend, lvreduce, lvremove, lvresize, lvs, pvcreate, pvs, vgcreate, vgs: harmonize descriptions (#5316) | 2021-03-08T20:25:12 | [84d537deb190](https://github.com/tldr-pages/tldr/commit/84d537deb1902fcde2a9a997dc5ec2a859a31ad7)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | lvs: add page (#4205) | 2020-07-21T21:45:10 | [4deb3d091670](https://github.com/tldr-pages/tldr/commit/4deb3d09167036b3495ef11ef39b19ac511318a4)

