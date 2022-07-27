---
author: ['Stig124', 'C-xC-c', 'siavashsoleymani']
date: 1625841955
title: "eix, TLDR Pages"
description: "eix, Utilities for searching local Gentoo packages."
categories: "linux"
---
> Update local package cache using `eix-update`.

> More information: <https://wiki.gentoo.org/wiki/Eix>.

- Search for a package:

```bash
eix package_name
```

- Search for installed packages:

```bash
eix --installed package_name
```

- Search in package descriptions:

```bash
eix --description "description"
```

- Search by package license:

```bash
eix --license license
```

- Exclude results from search:

```bash
eix --not --license license
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | eix: fix typo | 2020-10-27T12:01:11 | [2a1e5782a849](https://github.com/tldr-pages/tldr/commit/2a1e5782a849254b8b64353b8f78b0994a028420)
[C-xC-c](mailto:58750933+C-xC-c@users.noreply.github.com) | eix: add page (#4255) | 2020-08-16T01:58:06 | [b4bee09e498e](https://github.com/tldr-pages/tldr/commit/b4bee09e498e36d40f10741b539615a199813f0e)

