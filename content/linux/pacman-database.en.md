---
author: ['Axel Navarro']
date: 1615230352
title: "pacman --database, TLDR Pages"
description: "pacman --database, Operate on the Arch Linux package database."
categories: "linux"
---
> Modify certain attributes of the installed packages.

> More information: <https://man.archlinux.org/man/pacman.8>.

- Display help:

```bash
pacman --database --help
```

- Mark a package as implicitly installed:

```bash
sudo pacman --database --asdeps package_name
```

- Mark a package as explicitly installed:

```bash
sudo pacman --database --asexplicit package_name
```

- Check that all the package dependencies are installed:

```bash
pacman --database --check
```

- Check the repositories to ensure all specified dependencies are available:

```bash
pacman --database --check --check
```

- Display only error messages:

```bash
pacman --database --check --quiet
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-database: add page (#5302) | 2021-03-08T20:05:52 | [71f68b3fc4ad](https://github.com/tldr-pages/tldr/commit/71f68b3fc4ad4d79da540bf572d8135981215495)

