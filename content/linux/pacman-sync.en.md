---
author: ['Axel Navarro']
date: 1614291686
title: "pacman --sync"
description: "pacman --sync, Arch Linux package manager utility."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pacman.8>.

- Install a new package:

```bash
sudo pacman --sync package_name
```

- Synchronize and update all packages (add `--downloadonly` to download the packages and not update them):

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Update all packages and install a new one without prompting:

```bash
sudo pacman --sync --refresh --sysupgrade --noconfirm package_name
```

- Search the package database for a regular expression or keyword:

```bash
pacman --sync --search "search_pattern"
```

- Display information about a package:

```bash
pacman --sync --info package_name
```

- Overwrite conflicting files during a package update:

```bash
sudo pacman --sync --refresh --sysupgrade --overwrite path/to/file
```

- Synchronize and update all packages, but ignore a specific package (can be used more than once):

```bash
sudo pacman --sync --refresh --sysupgrade --ignore package_name
```

- Remove not installed packages and unused repositories from the cache (use two `--clean` flags to clean all packages):

```bash
sudo pacman --sync --clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-sync: add page (#5268) | 2021-02-25T23:21:26 | [5cc5b025f9e5](https://github.com/tldr-pages/tldr/commit/5cc5b025f9e54e703e08972eba5eb374450f6ee4)

