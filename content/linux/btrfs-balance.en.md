---
author: ['Bao']
date: 1640556246
title: "btrfs balance"
description: "btrfs balance, Balance block groups on a btrfs filesystem."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-balance>.

- Show the status of a running or paused balance operation:

```bash
sudo btrfs balance status path/to/btrfs_filesystem
```

- Balance all block groups (slow; rewrites all blocks in filesystem):

```bash
sudo btrfs balance start path/to/btrfs_filesystem
```

- Balance data block groups which are less than 15% utilized, running the operation in the background:

```bash
sudo btrfs balance start --bg -dusage=15 path/to/btrfs_filesystem
```

- Balance a max of 10 metadata chunks with less than 20% utilization and at least 1 chunk on a given device `devid` (see `btrfs filesystem show`):

```bash
sudo btrfs balance start -musage=20,limit=10,devid=devid path/to/btrfs_filesystem
```

- Convert data blocks to the raid6 and metadata to raid1c3 (see mkfs.btrfs(8) for profiles):

```bash
sudo btrfs balance start -dconvert=raid6 -mconvert=raid1c3 path/to/btrfs_filesystem
```

- Convert data blocks to raid1, skipping already converted chunks (e.g. after a previous cancelled conversion operation):

```bash
sudo btrfs balance start -dconvert=raid1,soft path/to/btrfs_filesystem
```

- Cancel, pause, or resume a running or paused balance operation:

```bash
sudo btrfs balance cancel|pause|resume path/to/btrfs_filesystem
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bao](mailto:qubidt@gmail.com) | btrfs-balance: add page (#7453) | 2021-12-26T23:04:06 | [e86b50be3024](https://github.com/tldr-pages/tldr/commit/e86b50be30242c899f0fc28d39a2b001d1ef23d3)

