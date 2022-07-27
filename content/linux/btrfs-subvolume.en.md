---
author: ['Starbeamrainbowlabs']
date: 1610964900
title: "btrfs subvolume, TLDR Pages"
description: "btrfs subvolume, Manage btrfs subvolumes and snapshots."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-subvolume>.

- Create a new empty subvolume:

```bash
sudo btrfs subvolume create path/to/new_subvolume
```

- List all subvolumes and snapshots in the specified filesystem:

```bash
sudo btrfs subvolume list path/to/btrfs_filesystem
```

- Delete a subvolume:

```bash
sudo btrfs subvolume delete path/to/subvolume
```

- Create a read-only snapshot of an existing subvolume:

```bash
sudo btrfs subvolume snapshot -r path/to/source_subvolume path/to/target
```

- Create a read-write snapshot of an existing subvolume:

```bash
sudo btrfs subvolume snapshot path/to/source_subvolume path/to/target
```

- Show detailed information about a subvolume:

```bash
sudo btrfs subvolume show path/to/subvolume
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | btrfs-subvolume: add page (#5153) | 2021-01-18T11:15:00 | [7548a66049a7](https://github.com/tldr-pages/tldr/commit/7548a66049a724a8742061512f901d40e1fea6a3)

