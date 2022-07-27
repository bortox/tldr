---
author: ['Waldir Pimenta', 'Peter Babič']
date: 1618918134
title: "genfstab, TLDR Pages"
description: "genfstab, Arch Linux install script to generate output suitable for addition to an fstab file."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/extra/arch-install-scripts/genfstab.8>.

- Display an fstab compatible output based on a volume label:

```bash
genfstab -L path/to/mount_point
```

- Display an fstab compatible output based on a volume UUID:

```bash
genfstab -U path/to/mount_point
```

- A usual way to generate an fstab file, requires root permissions:

```bash
genfstab -U /mnt >> /mnt/etc/fstab
```

- Append a volume into an fstab file to mount it automatically:

```bash
genfstab -U path/to/mount_point | sudo tee -a /etc/fstab
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | genfstab, pacstrap: mention that these are Arch-specific tools (#5795) | 2021-04-20T13:28:54 | [48f2869cf9d2](https://github.com/tldr-pages/tldr/commit/48f2869cf9d225e5b0bb0c879aa70fb23fd5d36f)
[Peter Babič](mailto:peter@babic.dev) | genfstab: add page (#5215) | 2021-02-03T01:30:58 | [81c139c072b5](https://github.com/tldr-pages/tldr/commit/81c139c072b554df335ab4f98653d9d31459affd)

