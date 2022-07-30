---
author: ['Richard Mörbitz', 'marchersimon']
date: 1618584134
title: "pmount"
description: "pmount, Mount arbitrary hotpluggable devices as a normal user."
categories: "linux"
---
> More information: <https://manned.org/pmount>.

- Mount a device below `/media/` (using device as mount point):

```bash
pmount /dev/to/block/device
```

- Mount a device with a specific filesystem type to `/media/label`:

```bash
pmount --type filesystem /dev/to/block/device label
```

- Mount a CD-ROM (filesystem type ISO9660) in read-only mode:

```bash
pmount --type iso9660 --read-only /dev/cdrom
```

- Mount an NTFS-formatted disk, forcing read-write access:

```bash
pmount --type ntfs --read-write /dev/sdX
```

- Display all mounted removable devices:

```bash
pmount
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Richard Mörbitz](mailto:richard.moerbitz@tu-dresden.de) | pmount: add page (#4878) | 2020-11-01T15:35:14 | [61ad03ec4d0a](https://github.com/tldr-pages/tldr/commit/61ad03ec4d0a184a276e59b4761882b909dd00da)

