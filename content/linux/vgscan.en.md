---
author: ['Seth Falco', 'Adam Herst']
date: 1648358715
title: "vgscan"
description: "vgscan, Scan for volume groups on all supported Logical Volume Manager (LVM) block devices."
categories: "linux"
---
> See also `lvm`, `vgchange`.

> More information: <https://manned.org/vgscan>.

- Scan for volume groups and print information about each group found:

```bash
sudo vgscan
```

- Scan for volume groups and add the special files in `/dev`, if they don't already exist, needed to access the logical volumes in the found groups:

```bash
sudo vgscan --mknodes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Adam Herst](mailto:adamherst@adamherst.com) | vgscan, vgchange: add page (#6128) | 2021-06-25T21:49:56 | [09eb57be3d5c](https://github.com/tldr-pages/tldr/commit/09eb57be3d5cac3ecced4d9c3b6be744b8330dc8)

