---
author: ['Igor Shubovych', 'Cvetomir Denchev', 'Starbeamrainbowlabs', 'Patrice Denis', 'Ruben Vereecken']
date: 1618665963
title: "apt-cache"
description: "apt-cache, Debian and Ubuntu package query tool."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

- Search for a package in your current sources:

```bash
apt-cache search query
```

- Show information about a package:

```bash
apt-cache show package
```

- Show whether a package is installed and up to date:

```bash
apt-cache policy package
```

- Show dependencies for a package:

```bash
apt-cache depends package
```

- Show packages that depend on a particular package:

```bash
apt-cache rdepends package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | added more apt-cache options | 2016-03-02T10:51:25 | [bdcc3b7c7c96](https://github.com/tldr-pages/tldr/commit/bdcc3b7c7c9619bf6aab13d3b1c0917dbc876d0d)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Linting after merging #507 | 2015-12-31T11:33:21 | [c7f5c3440206](https://github.com/tldr-pages/tldr/commit/c7f5c3440206a0bc32f7fdd52768ada09cd43a15)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Add apt-cache | 2015-12-31T11:24:25 | [bdfa9c394f6f](https://github.com/tldr-pages/tldr/commit/bdfa9c394f6f2b275228937be8161a1d9ba442d1)

