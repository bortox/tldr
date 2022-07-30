---
author: ['Stig124', 'Seth Falco', 'Adam I']
date: 1629050349
title: "blkdiscard"
description: "blkdiscard, Discards device sectors on storage devices. Useful for SSDs."
categories: "linux"
---
> More information: <https://manned.org/blkdiscard>.

- Discard all sectors on a device, removing all data:

```bash
blkdiscard /dev/device
```

- Securely discard all blocks on a device, removing all data:

```bash
blkdiscard --secure /dev/device
```

- Discard the first 100 MB of a device:

```bash
blkdiscard --length 100MB /dev/device
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Adam I](mailto:15039983+TheOtherUnknown@users.noreply.github.com) | blkdiscard: add page (#3292) | 2019-10-03T22:37:08 | [43be99e96395](https://github.com/tldr-pages/tldr/commit/43be99e9639567b18c8ffc8528516e8ed3d0f056)

