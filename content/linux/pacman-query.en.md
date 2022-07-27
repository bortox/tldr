---
author: ['Axel Navarro']
date: 1613695474
title: "pacman --query, TLDR Pages"
description: "pacman --query, Arch Linux package manager utility."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pacman.8>.

- List installed packages and versions:

```bash
pacman --query
```

- List only packages and versions that were explicitly installed:

```bash
pacman --query --explicit
```

- Find which package owns a file:

```bash
pacman --query --owns filename
```

- Display information about an installed package:

```bash
pacman --query --info package_name
```

- List files owned by a package:

```bash
pacman --query --list package_name
```

- List orphan packages (installed as dependencies but not required by any package):

```bash
pacman --query --unrequired --deps --quiet
```

- List installed packages not found in the repositories:

```bash
pacman --query --foreign
```

- List outdated packages:

```bash
pacman --query --upgrades
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-query: add page (#5269) | 2021-02-19T01:44:34 | [0f4bf14bd610](https://github.com/tldr-pages/tldr/commit/0f4bf14bd610e2c73457ead56a38f70e7efc07e8)

