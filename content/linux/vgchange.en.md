---
author: ['Adam Herst']
date: 1624650596
title: "vgchange"
description: "vgchange, Change the attributes of a Logical Volume Manager (LVM) volume group."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://manned.org/vgchange>.

- Change the activation status of logical volumes in all volume groups:

```bash
sudo vgchange --activate y|n
```

- Change the activation status of logical volumes in the specified volume group (determine with `vgscan`):

```bash
sudo vgchange --activate y|n volume_group}
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | vgscan, vgchange: add page (#6128) | 2021-06-25T21:49:56 | [09eb57be3d5c](https://github.com/tldr-pages/tldr/commit/09eb57be3d5cac3ecced4d9c3b6be744b8330dc8)

