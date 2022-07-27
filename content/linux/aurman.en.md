---
author: ['Axel Navarro']
date: 1616692646
title: "aurman, TLDR Pages"
description: "aurman, An Arch Linux utility to build and install packages from the Arch User Repository."
categories: "linux"
---
> See also `pacman`.

> More information: <https://github.com/polygamma/aurman>.

- Synchronize and update all packages:

```bash
aurman --sync --refresh --sysupgrade
```

- Synchronize and update all packages without show changes of `PKGBUILD` files:

```bash
aurman --sync --refresh --sysupgrade --noedit
```

- Install a new package:

```bash
aurman --sync package_name
```

- Install a new package without show changes of `PKGBUILD` files:

```bash
aurman --sync --noedit package_name
```

- Install a new package without prompting:

```bash
aurman --sync --noedit --noconfirm package_name
```

- Search the package database for a keyword from the official repositories and AUR:

```bash
aurman --sync --search keyword
```

- Remove a package and its dependencies:

```bash
aurman --remove --recursive --nosave package_name
```

- Clear the package cache (use two `--clean` flags to clean all packages):

```bash
aurman --sync --clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | aurman: add page (#5386) | 2021-03-25T18:17:26 | [d398c81811d2](https://github.com/tldr-pages/tldr/commit/d398c81811d2aeb7500cf45c83ed850f09c6e99a)

