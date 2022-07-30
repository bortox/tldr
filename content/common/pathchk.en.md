---
author: ['Dario Vladović', 'Jon LaBelle', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "pathchk"
description: "pathchk, Check the validity and portability of one or more pathnames."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/pathchk>.

- Check pathnames for validity in the current system:

```bash
pathchk path1 path2 …
```

- Check pathnames for validity on a wider range of POSIX compliant systems:

```bash
pathchk -p path1 path2 …
```

- Check pathnames for validity on all POSIX compliant systems:

```bash
pathchk --portability path1 path2 …
```

- Only check for empty pathnames or leading dashes (-):

```bash
pathchk -P path1 path2 …
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pathchk: add more information link (#5619) | 2021-03-30T16:13:36 | [6d3765b2d869](https://github.com/tldr-pages/tldr/commit/6d3765b2d869b3b0b0237cad5594d75b38de3f46)
[Jon LaBelle](mailto:contact@jonlabelle.com) | pathchk: move to pages/common `pathchk` is not exclusive to the Linux platforms; it's distributed with most (if not all) BSD [...] | 2019-02-18T08:46:25 | [f3d7ddd62202](https://github.com/tldr-pages/tldr/commit/f3d7ddd622026e7ade0916c35262edafe311124c)

