---
author: ['George Vlahavas', 'Aline Pêgas', 'Emily Grace Seville', 'Seth Falco']
date: 1647882468
title: "slapt-get"
description: "slapt-get, An apt like system for Slackware package management."
categories: "linux"
---
> Package sources need to be configured in the slapt-getrc file.

> More information: <https://software.jaos.org>.

- Update the list of available packages and versions:

```bash
slapt-get --update
```

- Install a package, or update it to the latest available version:

```bash
slapt-get --install package_name
```

- Remove a package:

```bash
slapt-get --remove package_name
```

- Upgrade all installed packages to their latest available versions:

```bash
slapt-get --upgrade
```

- Locate packages by the package name, disk set, or version:

```bash
slapt-get --search package_name
```

- Show information about a package:

```bash
slapt-get --show package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[George Vlahavas](mailto:vlahavas@gmail.com) | slapt-src, spi: add page, slapt-get: fix example (#5014) | 2020-12-14T13:05:58 | [cb83e50f5522](https://github.com/tldr-pages/tldr/commit/cb83e50f5522477e0f561f0e7e9137ed651549e9)
[Aline Pêgas](mailto:30935432+alinepegas@users.noreply.github.com) | slapt-get: add page (#2378) | 2018-10-04T12:51:14 | [4b82a76f12a5](https://github.com/tldr-pages/tldr/commit/4b82a76f12a504037de4e6f78a9e3afd4cbf2ade)

