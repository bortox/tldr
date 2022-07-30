---
author: ['Axel Navarro']
date: 1615235513
title: "pacman --deptest"
description: "pacman --deptest, Check each dependency specified and return a list of dependencies that are not currently satisfied on the system."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pacman.8>.

- Print the package names of the dependencies that aren't installed:

```bash
pacman --deptest package_name1 package_name2
```

- Check if the installed package satisfies the given minimum version:

```bash
pacman --deptest "bash>=5"
```

- Check if a later version of a package is installed:

```bash
pacman --deptest "bash>5"
```

- Display help:

```bash
pacman --deptest --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-deptest: add page (#5304) | 2021-03-08T21:31:53 | [01496626a27b](https://github.com/tldr-pages/tldr/commit/01496626a27bfeb681ecf51130dc32c0d114d42b)

