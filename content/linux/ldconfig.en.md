---
author: ['Lucas Gabriel Schneider', 'Agniva De Sarker']
date: 1629110041
title: "ldconfig"
description: "ldconfig, Configure symlinks and cache for shared library dependencies."
categories: "linux"
---
> More information: <https://manned.org/ldconfig>.

- Update symlinks and rebuild the cache (usually run when a new library is installed):

```bash
sudo ldconfig
```

- Update the symlinks for a given directory:

```bash
sudo ldconfig -n path/to/directory
```

- Print the libraries in the cache and check whether a given library is present:

```bash
ldconfig -p | grep library_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ldconfig: add page (#1536) | 2017-10-11T14:01:20 | [3e90d69a341f](https://github.com/tldr-pages/tldr/commit/3e90d69a341fc136cd9ec8b6fec305911e92c555)

