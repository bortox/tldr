---
author: ['Starbeamrainbowlabs']
date: 1612352907
title: "btrfs device, TLDR Pages"
description: "btrfs device, Manage devices in a btrfs filesystem."
categories: "linux"
---
> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-device>.

- Add one or more devices to a btrfs filesystem:

```bash
sudo btrfs device add path/to/block_device1 [path/to/block_device2] path/to/btrfs_filesystem
```

- Remove a device from a btrfs filesystem:

```bash
sudo btrfs device remove path/to/device|device_id [...]
```

- Display error statistics:

```bash
sudo btrfs device stats path/to/btrfs_filesystem
```

- Scan all disks and inform the kernel of all detected btrfs filesystems:

```bash
sudo btrfs device scan --all-devices
```

- Display detailed per-disk allocation statistics:

```bash
sudo btrfs device usage path/to/btrfs_filesystem
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | btrfs-device: add page (#5170) | 2021-02-03T12:48:27 | [caa82706aff5](https://github.com/tldr-pages/tldr/commit/caa82706aff5dc6e33630deea920900a816b8985)

