---
author: ['Waldir Pimenta', 'Ruben Vereecken', 'Agniva De Sarker', 'Brian Choromanski', 'rprieto']
date: 1634674282
title: "umount, TLDR Pages"
description: "umount, Unlink a filesystem from its mount point, making it no longer accessible."
categories: "common"
---
> A filesystem cannot be unmounted when it is busy.

> More information: <https://manned.org/umount.8>.

- Unmount a filesystem, by passing the path to the source it is mounted from:

```bash
umount path/to/device_file
```

- Unmount a filesystem, by passing the path to the target where it is mounted:

```bash
umount path/to/mounted_directory
```

- Unmount all mounted filesystems (except the `proc` filesystem):

```bash
umount -a
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Brian Choromanski](mailto:BrianChoromanski@gmail.com) | auditd, sftp, time, umount, unzip, w, which, wpa_supplicant: add link (#7037) | 2021-10-19T22:11:22 | [7f29e1695f3a](https://github.com/tldr-pages/tldr/commit/7f29e1695f3a3e3a2ecc20c730b8484a59daa588)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | umount: make descriptions more explicit (#1408) * umount: make descriptions more explicit * umount: clarify main description, per PR disc. | 2017-06-23T12:17:00 | [ec794ec2dc89](https://github.com/tldr-pages/tldr/commit/ec794ec2dc89c77160ac3efc598249ff2a715736)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Apply the 'path/to/item' convention uniformly (#947) | 2016-07-13T10:53:22 | [fa8b2d8f92ab](https://github.com/tldr-pages/tldr/commit/fa8b2d8f92abfcbea46036b8a30c129ac53abdcb)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

