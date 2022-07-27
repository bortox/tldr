---
author: ['Schneider', 'Emily Grace Seville', 'Ruben Vereecken', 'Agniva De Sarker', 'ix', 'Lucas Gabriel Schneider']
date: 1647882468
title: "prt-get, TLDR Pages"
description: "prt-get, The CRUX package manager."
categories: "linux"
---
> More information: <https://crux.nu/doc/prt-get%20-%20User%20Manual.html>.

- Install a package:

```bash
prt-get install package_name
```

- Install a package with dependency handling:

```bash
prt-get depinst package_name
```

- Update a package manually:

```bash
prt-get upgrade package_name
```

- Remove a package:

```bash
prt-get remove package_name
```

- Upgrade the system from the local ports tree:

```bash
prt-get sysup
```

- Search the ports tree:

```bash
prt-get search package_name
```

- Search for a file in a package:

```bash
prt-get fsearch file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | prt-get: updated description | 2020-02-20T18:00:28 | [3d86411e7953](https://github.com/tldr-pages/tldr/commit/3d86411e795397b108d2e0b4b0e7442abf129d57)
[Schneider](mailto:lucas.schneider@sap.com) | prt-get: remove adjectives | 2020-02-20T18:00:28 | [99b79941b3c5](https://github.com/tldr-pages/tldr/commit/99b79941b3c5eab48871768914ee27316f575464)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted pkg-related pages. | 2016-01-21T13:44:43 | [cc4a1447e3e4](https://github.com/tldr-pages/tldr/commit/cc4a1447e3e4da262b82684a2102956db9ae549c)
[ix](mailto:arcetera@cock.li) | remove things according to tldr | 2016-01-07T23:49:26 | [4dc87c83ea2d](https://github.com/tldr-pages/tldr/commit/4dc87c83ea2dc1901ffabaabec407adcbefb99f6)
[ix](mailto:arcetera@cock.li) | add pages for crux package management utilities | 2016-01-07T01:32:05 | [bc568b98c858](https://github.com/tldr-pages/tldr/commit/bc568b98c8580e64a6538c9335a28a44d47dd36d)

