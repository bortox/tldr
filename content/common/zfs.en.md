---
author: ['Miles Glapa-Grossklag', 'Peter Tripp', 'rprieto', 'Srinivasan R', 'HairyFotr', 'Ruben Vereecken']
date: 1630523283
title: "zfs"
description: "zfs, Manage ZFS filesystems."
categories: "common"
---
> More information: <https://manned.org/zfs>.

- List all available zfs filesystems:

```bash
zfs list
```

- Create a new ZFS filesystem:

```bash
zfs create pool_name/filesystem_name
```

- Delete a ZFS filesystem:

```bash
zfs destroy pool_name/filesystem_name
```

- Create a Snapshot of a ZFS filesystem:

```bash
zfs snapshot pool_name/filesystem_name@snapshot_name
```

- Enable compression on a filesystem:

```bash
zfs set compression=on pool_name/filesystem_name
```

- Change mountpoint for a filesystem:

```bash
zfs set mountpoint=/my/mount/path pool_name/filesystem_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | common/z*: add more information link (#6445) | 2021-09-01T21:08:03 | [82e685e155b9](https://github.com/tldr-pages/tldr/commit/82e685e155b93e19aef385e655da9134d4808701)
[HairyFotr](mailto:hairyfotr@gmail.com) | Fix a few typos | 2017-07-23T16:22:44 | [e0ccb7147a25](https://github.com/tldr-pages/tldr/commit/e0ccb7147a25b5d738e3991f399f87e45f3a4140)
[Peter Tripp](mailto:petertripp@gmail.com) | Fix ping, zfs and zpool to match current style guide. | 2016-01-16T20:45:16 | [c6635ec81549](https://github.com/tldr-pages/tldr/commit/c6635ec8154918099af4fc5f4fbf2a7d9b12f112)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

