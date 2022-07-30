---
author: ['Bao']
date: 1640387274
title: "btrfs restore"
description: "btrfs restore, Try to salvage files from a damaged btrfs filesystem."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-restore>.

- Restore all files from a btrfs filesystem to a given directory:

```bash
sudo btrfs restore path/to/btrfs_device path/to/target_directory
```

- List (don't write) files to be restored from a btrfs filesystem:

```bash
sudo btrfs restore --dry-run path/to/btrfs_device path/to/target_directory
```

- Restore files matching a given regex ([c]ase-insensitive) files to be restored from a btrfs filesystem (all parent directories of target file(s) must match as well):

```bash
sudo btrfs restore --path-regex regex -c path/to/btrfs_device path/to/target_directory
```

- Restore files from a btrfs filesystem using a specific root tree `bytenr` (see `btrfs-find-root`):

```bash
sudo btrfs restore -t bytenr path/to/btrfs_device path/to/target_directory
```

- Restore files from a btrfs filesystem (along with metadata, extended attributes, and Symlinks), overwriting files in the target:

```bash
sudo btrfs restore --metadata --xattr --symlinks --overwrite path/to/btrfs_device path/to/target_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bao](mailto:qubidt@gmail.com) | btrfs-restore: add page (#7455) | 2021-12-25T00:07:54 | [dc66d32ddffa](https://github.com/tldr-pages/tldr/commit/dc66d32ddffa55b22af84ebe5c4918e064214a10)

