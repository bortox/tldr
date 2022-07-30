---
author: ['Axel Navarro']
date: 1615230188
title: "pacman --upgrade"
description: "pacman --upgrade, Arch Linux package manager utility."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pacman.8>.

- Display help:

```bash
pacman --upgrade --help
```

- Install one or more packages from files:

```bash
sudo pacman --upgrade path/to/package1.pkg.tar.zst path/to/package2.pkg.tar.zst
```

- Install a package without prompting:

```bash
sudo pacman --upgrade --noconfirm path/to/package.pkg.tar.zst
```

- Overwrite conflicting files during a package installation:

```bash
sudo pacman --upgrade --overwrite path/to/file path/to/package.pkg.tar.zst
```

- Install a package, skipping the dependency version checks:

```bash
sudo pacman --upgrade --nodeps path/to/package.pkg.tar.zst
```

- List packages that would be affected (does not install any packages):

```bash
pacman --query --print path/to/package.pkg.tar.zst
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-upgrade: add page (#5295) | 2021-03-08T20:03:08 | [36e7ef38da71](https://github.com/tldr-pages/tldr/commit/36e7ef38da719cb159aeb5f24105180b850d28f1)

