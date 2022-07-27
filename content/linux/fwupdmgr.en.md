---
author: ['Managor']
date: 1632830859
title: "fwupdmgr, TLDR Pages"
description: "fwupdmgr, A tool for updating device firmware, including UEFI, using `fwupd`."
categories: "linux"
---
> More information: <https://fwupd.org/>.

- Display all devices detected by fwupd:

```bash
fwupdmgr get-devices
```

- Download the latest firmware metadata from LVFS:

```bash
fwupdmgr refresh
```

- List the updates available for devices on your system:

```bash
fwupdmgr get-updates
```

- Install firmware updates:

```bash
fwupdmgr update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | fwupdmgr: add page (#6601) | 2021-09-28T14:07:39 | [b36a446e0c76](https://github.com/tldr-pages/tldr/commit/b36a446e0c76383a65f1fe3195d24c738efbcf55)

