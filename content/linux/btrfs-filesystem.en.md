---
author: ['Starbeamrainbowlabs']
date: 1611538926
title: "btrfs filesystem"
description: "btrfs filesystem, Manage btrfs filesystems."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-filesystem>.

- Show filesystem usage (optionally run as root to show detailed information):

```bash
btrfs filesystem usage path/to/btrfs_mount
```

- Show usage by individual devices:

```bash
sudo btrfs filesystem show path/to/btrfs_mount
```

- Defragment a single file on a btrfs filesystem (avoid while a deduplication agent is running):

```bash
sudo btrfs filesystem defragment -v path/to/file
```

- Defragment a directory recursively (does not cross subvolume boundaries):

```bash
sudo btrfs filesystem defragment -v -r path/to/directory
```

- Force syncing unwritten data blocks to disk(s):

```bash
sudo btrfs filesystem sync path/to/btrfs_mount
```

- Summarize disk usage for the files in a directory recursively:

```bash
sudo btrfs filesystem du --summarize path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | btrfs-filesystem: correct and improve (#5169) | 2021-01-25T02:42:06 | [5b414146f65d](https://github.com/tldr-pages/tldr/commit/5b414146f65d6bf92131b1cd8ffeffa5bab11021)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | btrfs-filesystem: add page (#5102) | 2021-01-07T12:04:21 | [16c1b0aaf423](https://github.com/tldr-pages/tldr/commit/16c1b0aaf4238299d002dfda6ca812bd5d20c1e4)

