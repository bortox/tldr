---
author: ['Stig124', 'Owen Voke']
date: 1625841955
title: "eject, TLDR Pages"
description: "eject, Eject cds, floppy disks and tape drives."
categories: "linux"
---
> More information: <https://manned.org/eject>.

- Display the default device:

```bash
eject -d
```

- Eject the default device:

```bash
eject
```

- Eject a specific device (the default order is cd-rom, scsi, floppy and tape):

```bash
eject /dev/cdrom
```

- Toggle whether a device's tray is open or closed:

```bash
eject -T /dev/cdrom
```

- Eject a cd drive:

```bash
eject -r /dev/cdrom
```

- Eject a floppy drive:

```bash
eject -f /mnt/floppy
```

- Eject a tape drive:

```bash
eject -q /mnt/tape
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Owen Voke](mailto:owzie123@gmail.com) | eject: add page (#2291) | 2018-09-05T14:07:44 | [b50c88a51bb6](https://github.com/tldr-pages/tldr/commit/b50c88a51bb67df5648373379371ee8a1e66389f)

