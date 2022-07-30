---
author: ['Miles Glapa-Grossklag', 'Esteban Flores', 'Peter Tripp', 'rprieto', 'lord63', 'Vykook', 'Ruben Vereecken']
date: 1630523283
title: "zpool"
description: "zpool, Manage ZFS pools."
categories: "common"
---
> More information: <https://manned.org/zpool>.

- Show the configuration and status of all ZFS zpools:

```bash
zpool status
```

- Check a ZFS pool for errors (verifies the checksum of EVERY block). Very CPU and disk intensive:

```bash
zpool scrub pool_name
```

- List zpools available for import:

```bash
zpool import
```

- Import a zpool:

```bash
zpool import pool_name
```

- Export a zpool (unmount all filesystems):

```bash
zpool export pool_name
```

- Show the history of all pool operations:

```bash
zpool history pool_name
```

- Create a mirrored pool:

```bash
zpool create pool_name mirror disk1 disk2 mirror disk3 disk4
```

- Add a cache (L2ARC) device to a zpool:

```bash
zpool add pool_name cache cache_disk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | common/z*: add more information link (#6445) | 2021-09-01T21:08:03 | [82e685e155b9](https://github.com/tldr-pages/tldr/commit/82e685e155b93e19aef385e655da9134d4808701)
[Esteban Flores](mailto:esflores@microsoft.com) | zpool: added cache device example (#2715) | 2019-01-17T12:09:36 | [7f41209465d1](https://github.com/tldr-pages/tldr/commit/7f41209465d1b1282a93fb8046cc7052cb4ebab9)
[Vykook](mailto:vykook@zabij.se) | zpool: fix typo | 2017-11-30T13:28:50 | [17925a9716eb](https://github.com/tldr-pages/tldr/commit/17925a9716eb891f0467e04b7bc9e47d77ea009d)
[Peter Tripp](mailto:petertripp@gmail.com) | Fix ping, zfs and zpool to match current style guide. | 2016-01-16T20:45:16 | [c6635ec81549](https://github.com/tldr-pages/tldr/commit/c6635ec8154918099af4fc5f4fbf2a7d9b12f112)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

