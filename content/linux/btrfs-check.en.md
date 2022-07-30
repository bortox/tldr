---
author: ['Vinh Quang Tran']
date: 1634206104
title: "btrfs check"
description: "btrfs check, Check or repair a btrfs filesystem."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-check>.

- Check a btrfs filesystem:

```bash
sudo btrfs check path/to/partition
```

- Check and repair a btrfs filesystem (dangerous):

```bash
sudo btrfs check --repair path/to/partition
```

- Show the progress of the check:

```bash
sudo btrfs check --progress path/to/partition
```

- Verify the checksum of each data block (if the filesystem is good):

```bash
sudo btrfs check --check-data-csum path/to/partition
```

- Use the `n`-th superblock (`n` can be 0, 1 or 2):

```bash
sudo btrfs check --super n path/to/partition
```

- Rebuild the checksum tree:

```bash
sudo btrfs check --repair --init-csum-tree path/to/partition
```

- Rebuild the extent tree:

```bash
sudo btrfs check --repair --init-extent-tree path/to/partition
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Vinh Quang Tran](mailto:starcraft6723@hotmail.com) | btrfs-check: add page (#6959) | 2021-10-14T12:08:24 | [af68b27c9cbf](https://github.com/tldr-pages/tldr/commit/af68b27c9cbfc7ee88a69878ea012557e138dd00)

