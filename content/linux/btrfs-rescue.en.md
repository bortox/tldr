---
author: ['kyteinsky']
date: 1635196470
title: "btrfs rescue, TLDR Pages"
description: "btrfs rescue, Try to recover a damaged btrfs filesystem."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-rescue>.

- Rebuild the filesystem metadata tree (very slow):

```bash
sudo btrfs rescue chunk-recover path/to/partition
```

- Fix device size alignment related problems (e.g. unable to mount the filesystem with super total bytes mismatch):

```bash
sudo btrfs rescue fix-device-size path/to/partition
```

- Recover a corrupted superblock from correct copies (recover the root of filesystem tree):

```bash
sudo btrfs rescue super-recover path/to/partition
```

- Recover from an interrupted transactions (fixes log replay problems):

```bash
sudo btrfs rescue zero-log path/to/partition
```

- Create a `/dev/btrfs-control` control device when `mknod` is not installed:

```bash
sudo btrfs rescue create-control-device
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[kyteinsky](mailto:kyteinsky@gmail.com) | btrfs-rescue: add page (#6963) | 2021-10-25T23:14:30 | [9dc2d0cd8644](https://github.com/tldr-pages/tldr/commit/9dc2d0cd86445e8786e802f569178f4bd4341a8b)

