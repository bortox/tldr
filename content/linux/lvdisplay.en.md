---
author: ['Adam Herst']
date: 1616634424
title: "lvdisplay, TLDR Pages"
description: "lvdisplay, Display information about Logical Volume Manager (LVM) logical volumes."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/lvdisplay.8.html>.

- Display information about all logical volumes:

```bash
sudo lvdisplay
```

- Display information about all logical volumes in volume group vg1:

```bash
sudo lvdisplay vg1
```

- Display information about logical volume lv1 in volume group vg1:

```bash
sudo lvdisplay vg1/lv1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | lvdisplay: fix punctuation | 2021-03-25T02:07:04 | [97868a7e4136](https://github.com/tldr-pages/tldr/commit/97868a7e413646b29a7b3d99298a80507e879056)
[Adam Herst](mailto:adamherst@adamherst.com) | lvdisplay: fix markup for example command line | 2021-03-25T02:07:04 | [b07f2acb4708](https://github.com/tldr-pages/tldr/commit/b07f2acb4708403ca6faf18adf5536dd0efa61e1)
[Adam Herst](mailto:adamherst@adamherst.com) | lvdisplay, pvdisplay, vgdisplay: Add new pages. | 2021-03-25T02:07:04 | [4719d2047181](https://github.com/tldr-pages/tldr/commit/4719d2047181569de84cc0fb54d238c2d3878012)

