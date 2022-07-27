---
author: ['George Vlahavas', 'Seth Falco']
date: 1629050349
title: "spi, TLDR Pages"
description: "spi, A meta package manager that handles both packages and slackbuilds."
categories: "linux"
---
> More information: <https://github.com/gapan/spi>.

- Update the list of available packages and slackbuilds:

```bash
spi --update
```

- Install a package or slackbuild:

```bash
spi --install package/slackbuild_name
```

- Upgrade all installed packages to the latest versions available:

```bash
spi --upgrade
```

- Locate packages or slackbuilds by package name or description:

```bash
spi search_terms
```

- Display information about a package or slackbuild:

```bash
spi --show package/slackbuild_name
```

- Purge the local package and slackbuild caches:

```bash
spi --clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[George Vlahavas](mailto:vlahavas@gmail.com) | slapt-src, spi: add page, slapt-get: fix example (#5014) | 2020-12-14T13:05:58 | [cb83e50f5522](https://github.com/tldr-pages/tldr/commit/cb83e50f5522477e0f561f0e7e9137ed651549e9)

