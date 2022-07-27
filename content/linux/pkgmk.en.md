---
author: ['ix', 'Ruben Vereecken', 'Emily Grace Seville']
date: 1647882468
title: "pkgmk, TLDR Pages"
description: "pkgmk, Make a binary package for use with pkgadd on CRUX."
categories: "linux"
---
> More information: <https://docs.oracle.com/cd/E19683-01/816-0210/6m6nb7mha/index.html>.

- Make and download a package:

```bash
pkgmk -d
```

- Install the package after making it:

```bash
pkgmk -d -i
```

- Upgrade the package after making it:

```bash
pkgmk -d -u
```

- Ignore the footprint when making a package:

```bash
pkgmk -d -if
```

- Ignore the MD5 sum when making a package:

```bash
pkgmk -d -im
```

- Update the package's footprint:

```bash
pkgmk -uf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted pkg-related pages. | 2016-01-21T13:44:43 | [cc4a1447e3e4](https://github.com/tldr-pages/tldr/commit/cc4a1447e3e4da262b82684a2102956db9ae549c)
[ix](mailto:arcetera@cock.li) | remove things according to tldr | 2016-01-07T23:49:26 | [4dc87c83ea2d](https://github.com/tldr-pages/tldr/commit/4dc87c83ea2dc1901ffabaabec407adcbefb99f6)
[ix](mailto:arcetera@cock.li) | add pages for crux package management utilities | 2016-01-07T01:32:05 | [bc568b98c858](https://github.com/tldr-pages/tldr/commit/bc568b98c8580e64a6538c9335a28a44d47dd36d)

