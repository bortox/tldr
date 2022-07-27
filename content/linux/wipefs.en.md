---
author: ['James Hibbard', 'derNiklaas', 'Agno94']
date: 1633404950
title: "wipefs, TLDR Pages"
description: "wipefs, Wipe filesystem, raid, or partition-table signatures from a device."
categories: "linux"
---
> More information: <https://manned.org/wipefs>.

- Display signatures for specified device:

```bash
sudo wipefs /dev/sdX
```

- Wipe all available signatures for specified device:

```bash
sudo wipefs --all /dev/sdX
```

- Perform dry run:

```bash
sudo wipefs --all --no-act /dev/sdX
```

- Force wipe, even if the filesystem is mounted:

```bash
sudo wipefs --all --force /dev/sdX
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[Agno94](mailto:agnophi@gmail.com) | badblocks, ddrescue, fdisk, fsck, ioping, smartctl, wipefs: change /dev/sda into /dev/sdX (#4861) | 2020-10-29T12:21:45 | [c312c50b9906](https://github.com/tldr-pages/tldr/commit/c312c50b99062c4dca949685ddc31385b179b7d5)
[James Hibbard](mailto:1940994+jameshibbard@users.noreply.github.com) | wipefs: add page (#4106) | 2020-06-18T13:58:03 | [7338823adf18](https://github.com/tldr-pages/tldr/commit/7338823adf1879c7ac6e947ece417be02f5d165f)

