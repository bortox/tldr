---
author: ['Austin', 'Kyle', 'Ruben Vereecken', 'Sam D', 'rprieto']
date: 1629747204
title: "diskutil, TLDR Pages"
description: "diskutil, Utility to manage local disks and volumes."
categories: "osx"
---
> More information: <https://ss64.com/osx/diskutil.html>.

- List all currently available disks, partitions and mounted volumes:

```bash
diskutil list
```

- Repair the filesystem data structures of a volume:

```bash
diskutil repairVolume /dev/diskX
```

- Unmount a volume:

```bash
diskutil unmountDisk /dev/diskX
```

- Eject a CD/DVD (unmount first):

```bash
diskutil eject /dev/disk1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Sam D](mailto:llamaswill@gmail.com) | removes no-longer-there diskutil verb As of El Capitan, `sudo diskutil repairPermissions /` returns `diskutil: did not recognize verb [...] | 2015-12-31T00:21:59 | [10232ce7c21a](https://github.com/tldr-pages/tldr/commit/10232ce7c21adcccdf23c14fc9c372676883c645)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

