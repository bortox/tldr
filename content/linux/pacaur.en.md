---
author: ['Austin Albrecht', 'Emily Grace Seville']
date: 1647882468
title: "pacaur"
description: "pacaur, A utility for Arch Linux to build and install packages from the Arch User Repository."
categories: "linux"
---
> More information: <https://github.com/rmarquis/pacaur>.

- Synchronize and update all packages (includes AUR):

```bash
pacaur -Syu
```

- Synchronize and update only AUR packages:

```bash
pacaur -Syua
```

- Install a new package (includes AUR):

```bash
pacaur -S package_name
```

- Remove a package and its dependencies (includes AUR packages):

```bash
pacaur -Rs package_name
```

- Search the package database for a keyword (includes AUR):

```bash
pacaur -Ss keyword
```

- List all currently installed packages (includes AUR packages):

```bash
pacaur -Qs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Austin Albrecht](mailto:austin.aa@me.com) | pacaur: add page | 2018-01-13T19:04:59 | [508cc16d50d2](https://github.com/tldr-pages/tldr/commit/508cc16d50d2151f12c43afba2810d1e69df6aa3)

