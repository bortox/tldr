---
author: ['Axel Navarro']
date: 1613730567
title: "pacman --remove, TLDR Pages"
description: "pacman --remove, Arch Linux package manager utility."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pacman.8>.

- Display help for this subcommand:

```bash
pacman --remove --help
```

- Remove a package and its dependencies:

```bash
sudo pacman --remove --recursive package_name
```

- Remove a package and both its dependencies and configuration files:

```bash
sudo pacman --remove --recursive --nosave package_name
```

- Remove a package without prompting:

```bash
sudo pacman --remove --noconfirm package_name
```

- Remove orphan packages (installed as dependencies but not required by any package):

```bash
sudo pacman --remove --recursive --nosave $(pacman --query --unrequired --deps --quiet)
```

- Remove a package and all packages that depend on it:

```bash
sudo pacman --remove --cascade package_name
```

- List packages that would be affected (does not remove any packages):

```bash
pacman --remove --print package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-remove: add page (#5273) | 2021-02-19T11:29:27 | [66b49e9dccbf](https://github.com/tldr-pages/tldr/commit/66b49e9dccbfade0128b5275326c531ad39717ce)

