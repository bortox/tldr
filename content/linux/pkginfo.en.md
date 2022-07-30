---
author: ['ix', 'Ruben Vereecken', 'Saksham Mittal', 'Agniva De Sarker']
date: 1635743383
title: "pkginfo"
description: "pkginfo, Query the package database on a CRUX system."
categories: "linux"
---
> More information: <https://crux.nu/Main/Handbook3-6#ntoc19>.

- List installed packages and their versions:

```bash
pkginfo -i
```

- List files owned by a package:

```bash
pkginfo -l package_name
```

- List the owner(s) of files matching a pattern:

```bash
pkginfo -o pattern
```

- Print the footprint of a file:

```bash
pkginfo -f file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Saksham Mittal](mailto:gotlougit@users.noreply.github.com) | pkginfo: add more information link (#7346) | 2021-11-01T06:09:43 | [0b1f5be91dea](https://github.com/tldr-pages/tldr/commit/0b1f5be91dea7c296549aa1d67c130da06535d95)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted pkg-related pages. | 2016-01-21T13:44:43 | [cc4a1447e3e4](https://github.com/tldr-pages/tldr/commit/cc4a1447e3e4da262b82684a2102956db9ae549c)
[ix](mailto:arcetera@cock.li) | remove things according to tldr | 2016-01-07T23:49:26 | [4dc87c83ea2d](https://github.com/tldr-pages/tldr/commit/4dc87c83ea2dc1901ffabaabec407adcbefb99f6)
[ix](mailto:arcetera@cock.li) | add pages for crux package management utilities | 2016-01-07T01:32:05 | [bc568b98c858](https://github.com/tldr-pages/tldr/commit/bc568b98c8580e64a6538c9335a28a44d47dd36d)

