---
author: ['Anirudh Haritas Murali']
date: 1634106080
title: "jmtpfs, TLDR Pages"
description: "jmtpfs, FUSE-based filesystem for accessing MTP devices."
categories: "common"
---
> More information: <https://manned.org/jmtpfs>.

- Mount an MTP device to a directory:

```bash
jmtpfs path/to/directory
```

- Set mount options:

```bash
jmtpfs -o allow_other,auto_unmount path/to/directory
```

- List available MTP devices:

```bash
jmtpfs --listDevices
```

- If multiple devices are present, mount a specific device:

```bash
jmtpfs -device=bus_id,device_id path/to/directory
```

- Unmount MTP device:

```bash
fusermount -u path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anirudh Haritas Murali](mailto:49116134+anihm136@users.noreply.github.com) | jmtpfs: add page (#6935) | 2021-10-13T08:21:20 | [b47a14a8c480](https://github.com/tldr-pages/tldr/commit/b47a14a8c48010ee6c33f8f5aa6354cdf9aa452a)

