---
author: ['Starbeamrainbowlabs']
date: 1616027752
title: "mkfs.btrfs, TLDR Pages"
description: "mkfs.btrfs, Create a btrfs filesystem."
categories: "linux"
---
> Defaults to `raid1`, which specifies 2 copies of a given data block spread across 2 different devices.

> More information: <https://btrfs.wiki.kernel.org/index.php/Manpage/mkfs.btrfs>.

- Create a btrfs filesystem on a single device:

```bash
sudo mkfs.btrfs --metadata single --data single /dev/sda
```

- Create a btrfs filesystem on multiple devices with raid1:

```bash
sudo mkfs.btrfs --metadata raid1 --data raid1 /dev/sda /dev/sdb /dev/sdN
```

- Set a label for the filesystem:

```bash
sudo mkfs.btrfs --label "label" /dev/sda [/dev/sdN]
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | mkfs.btrfs: add page (#5441) | 2021-03-18T01:35:52 | [1731aeacadac](https://github.com/tldr-pages/tldr/commit/1731aeacadacfacbadadde6d8ba57f743c56966c)

