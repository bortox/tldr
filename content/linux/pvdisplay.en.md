---
author: ['Adam Herst']
date: 1616634424
title: "pvdisplay, TLDR Pages"
description: "pvdisplay, Display information about Logical Volume Manager (LVM) physical volumes."
categories: "linux"
---
> See also: `lvm`.

> More information: <https://man7.org/linux/man-pages/man8/pvdisplay.8.html>.

- Display information about all physical volumes:

```bash
sudo pvdisplay
```

- Display information about the physical volume on drive `/dev/sdXY`:

```bash
sudo pvdisplay /dev/sdXY
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | pvdisplay: change references to block devices Use the new notation that has been approved but not merged into the style guide. | 2021-03-25T02:07:04 | [d1f4342a740d](https://github.com/tldr-pages/tldr/commit/d1f4342a740d7613cd4f881a1a571455dbe584ea)
[Adam Herst](mailto:adamherst@adamherst.com) | pvdisplay: remove trailing whitespace | 2021-03-25T02:07:04 | [f19a35cb76b8](https://github.com/tldr-pages/tldr/commit/f19a35cb76b89b9cfe8f81eb78dc8ebc326778b7)
[Adam Herst](mailto:adamherst@adamherst.com) | pvdisplay: fix punctionation in description | 2021-03-25T02:07:04 | [e4d866a0f771](https://github.com/tldr-pages/tldr/commit/e4d866a0f77166a32e0817f0391ec6a121d1ba06)
[Adam Herst](mailto:adamherst@adamherst.com) | pvdisplay: fix markup for device reference in example description. | 2021-03-25T02:07:04 | [310b342139d8](https://github.com/tldr-pages/tldr/commit/310b342139d87739d08da656b7030c8321017cc6)
[Adam Herst](mailto:adamherst@adamherst.com) | lvdisplay, pvdisplay, vgdisplay: Add new pages. | 2021-03-25T02:07:04 | [4719d2047181](https://github.com/tldr-pages/tldr/commit/4719d2047181569de84cc0fb54d238c2d3878012)

