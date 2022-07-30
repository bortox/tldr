---
author: ['Aakash Sharma']
date: 1633464798
title: "repo-add"
description: "repo-add, Package database maintenance utility which enables installation of said package via Pacman."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/repo-add>.

- Add all package binaries in the current directory and remove the old database file:

```bash
repo-add --remove path/to/database.db.tar.gz *.pkg.tar.zst
```

- Add all package binaries in the current directory in silent mode except for warning and error messages:

```bash
repo-add --quiet path/to/database.db.tar.gz *.pkg.tar.zst
```

- Add all package binaries in the current directory without showing color:

```bash
repo-add --nocolor path/to/database.db.tar.gz *.pkg.tar.zst
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Aakash Sharma](mailto:60808802+Shinyzenith@users.noreply.github.com) | repo-add: add page (#6622) | 2021-10-05T22:13:18 | [c66e7634e1e5](https://github.com/tldr-pages/tldr/commit/c66e7634e1e59aa749f2d66bce6aefab005905d1)

