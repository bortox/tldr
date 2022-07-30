---
author: ['Stig124', 'Arun Isaac']
date: 1625841955
title: "guix package"
description: "guix package, Install, upgrade and remove Guix packages, or rollback to previous configurations."
categories: "linux"
---
> More information: <https://guix.gnu.org/manual/html_node/Invoking-guix-package.html>.

- Install a new package:

```bash
guix package -i package_name
```

- Remove a package:

```bash
guix package -r package_name
```

- Search the package database for a regular expression:

```bash
guix package -s "search_pattern"
```

- List installed packages:

```bash
guix package -I
```

- List generations:

```bash
guix package -l
```

- Roll back to the previous generation:

```bash
guix package --roll-back
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | guix-package: add page (#2489) | 2018-10-26T21:14:42 | [435ec65f214e](https://github.com/tldr-pages/tldr/commit/435ec65f214e9fba56c3bca7207c3a7e5558b7c7)

