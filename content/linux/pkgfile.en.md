---
author: ['Peter Babič', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "pkgfile, TLDR Pages"
description: "pkgfile, Tool for searching files from packages in the official repositories on arch-based systems."
categories: "linux"
---
> See also `pacman files`, describing the usage of `pacman --files`.

> More information: <https://man.archlinux.org/man/extra/pkgfile/pkgfile.1>.

- Synchronize the pkgfile database:

```bash
sudo pkgfile --update
```

- Search for a package that owns a specific file:

```bash
pkgfile filename
```

- List all files provided by a package:

```bash
pkgfile --list package_name
```

- List only files provided by a package located within the `bin` or `sbin` directory:

```bash
pkgfile --list --binaries package_name
```

- Search for a package that owns a specific file using case-insensitive matching:

```bash
pkgfile --ignorecase filename
```

- Search for a package that owns a specific file in the `bin` or `sbin` directory:

```bash
pkgfile --binaries filename
```

- Search for a package that owns a specific file, displaying the package version:

```bash
pkgfile --verbose filename
```

- Search for a package that owns a specific file in a specific repository:

```bash
pkgfile --repo repository_name filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Peter Babič](mailto:peter@babic.dev) | pkgfile: fix example and update link (#5821) | 2021-04-28T16:39:51 | [d9e0324717ad](https://github.com/tldr-pages/tldr/commit/d9e0324717ad0610d052a8f7bb196cf62f4c7207)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pkgfile: add page (#5403) | 2021-03-13T22:31:08 | [5a3df75c14ab](https://github.com/tldr-pages/tldr/commit/5a3df75c14abf448556920bbfce016686e30f872)

