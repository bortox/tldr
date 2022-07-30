---
author: ['Eiman']
date: 1603908446
title: "udisksctl"
description: "udisksctl, A command-line program used to interact with the udisksd daemon process."
categories: "linux"
---
> More information: <http://storaged.org/doc/udisks2-api/latest/udisksctl.1.html>.

- Show high-level information about disk drives and block devices:

```bash
udisksctl status
```

- Show detailed information about a device:

```bash
udisksctl info --block-device /dev/sdX
```

- Show detailed information about a device partition:

```bash
udisksctl info --block-device /dev/sdXN
```

- Mount a device partition and prints the mount point:

```bash
udisksctl mount --block-device /dev/sdXN
```

- Unmount a device partition:

```bash
udisksctl unmount --block-device /dev/sdXN
```

- Monitor the daemon for events:

```bash
udisksctl monitor
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Eiman](mailto:eimanip@users.noreply.github.com) | udisktctl: add page (#4856) | 2020-10-28T19:07:26 | [c96586e605e1](https://github.com/tldr-pages/tldr/commit/c96586e605e1eb3f2497fe3fc0cd4b0599424203)

