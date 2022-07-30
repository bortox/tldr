---
author: ['Vinh Quang Tran']
date: 1635013495
title: "btrfs inspect-internal"
description: "btrfs inspect-internal, Query internal information of a btrfs filesystem."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-inspect-internal>.

- Print superblock's information:

```bash
sudo btrfs inspect-internal dump-super path/to/partition
```

- Print superblock's and all of its copies' information:

```bash
sudo btrfs inspect-internal dump-super --all path/to/partition
```

- Print filesystem's metadata information:

```bash
sudo btrfs inspect-internal dump-tree path/to/partition
```

- Print list of files in inode `n`-th:

```bash
sudo btrfs inspect-internal inode-resolve n path/to/btrfs_mount
```

- Print list of files at a given logical address:

```bash
sudo btrfs inspect-internal logical-resolve logical_address path/to/btrfs_mount
```

- Print stats of root, extent, csum and fs trees:

```bash
sudo btrfs inspect-internal tree-stats path/to/partition
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Vinh Quang Tran](mailto:starcraft6723@hotmail.com) | btrfs-inspect-internal: add page (#6975) | 2021-10-23T20:24:55 | [0ce559932bde](https://github.com/tldr-pages/tldr/commit/0ce559932bde9c185de40df67a8cacf138937aca)

