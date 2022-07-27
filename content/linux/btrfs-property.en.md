---
author: ['Bao']
date: 1640567669
title: "btrfs property, TLDR Pages"
description: "btrfs property, Get, set, or list properties for a given btrfs filesystem object (files, directories, subvolumes, filesystems, or devices)."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-property>.

- List available properties (and descriptions) for the given btrfs object:

```bash
sudo btrfs property list path/to/btrfs_object
```

- Get all properties for the given btrfs object:

```bash
sudo btrfs property get path/to/btrfs_object
```

- Get the `label` property for the given btrfs filesystem or device:

```bash
sudo btrfs property get path/to/btrfs_filesystem label
```

- Get all object type-specific properties for the given btrfs filesystem or device:

```bash
sudo btrfs property get -t subvol|filesystem|inode|device path/to/btrfs_filesystem
```

- Set the `compression` property for a given btrfs inode (either a file or directory):

```bash
sudo btrfs property set path/to/btrfs_inode compression zstd|zlib|lzo|none
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bao](mailto:qubidt@gmail.com) | btrfs-property: add page (#7454) | 2021-12-27T02:14:29 | [38d44d6c409d](https://github.com/tldr-pages/tldr/commit/38d44d6c409d6b354873bf9876ef2a8e951552a2)

