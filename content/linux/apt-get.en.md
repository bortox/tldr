---
author: ['Waldir Pimenta', 'Patrice Denis', 'lord63', 'saeed', 'Ruben Vereecken', 'Scott Schlesier', 'Zlatan Vasović', 'Romain Prieto', 'rprieto', 'Lucas Gabriel Schneider', 'Gustavo Dias Alexandre']
date: 1618665963
title: "apt-get, TLDR Pages"
description: "apt-get, Debian and Ubuntu package management utility."
categories: "linux"
---
> Search for packages using `apt-cache`.

> More information: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Update the list of available packages and versions (it's recommended to run this before other `apt-get` commands):

```bash
apt-get update
```

- Install a package, or update it to the latest available version:

```bash
apt-get install package
```

- Remove a package:

```bash
apt-get remove package
```

- Remove a package and its configuration files:

```bash
apt-get purge package
```

- Upgrade all installed packages to their newest available versions:

```bash
apt-get upgrade
```

- Clean the local repository - removing package files (`.deb`) from interrupted downloads that can no longer be downloaded:

```bash
apt-get autoclean
```

- Remove all packages that are no longer needed:

```bash
apt-get autoremove
```

- Upgrade installed packages (like `upgrade`), but remove obsolete packages and install additional packages to meet new dependencies:

```bash
apt-get dist-upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Gustavo Dias Alexandre](mailto:gfdiasa@gmail.com) | apt-get: add autoclean example (#4294) | 2020-09-05T00:46:48 | [6f2b6fc16998](https://github.com/tldr-pages/tldr/commit/6f2b6fc169988e36417f3674c3cf6b079dc2d656)
[saeed](mailto:39596095+smzm@users.noreply.github.com) | apt-get: add apt-get purge example (#2772) | 2019-02-11T14:28:03 | [1f94abff1f0b](https://github.com/tldr-pages/tldr/commit/1f94abff1f0b650b70caaebcdbc50eee1017be73)
[Scott Schlesier](mailto:scott@schlesier.ca) | apt-get: add pointer to apt-cache when searching for pacakges (#2231) | 2018-07-31T21:36:08 | [be8ab27c34b1](https://github.com/tldr-pages/tldr/commit/be8ab27c34b12a7db565d1fd149a5d5fb100eeaa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | apt-get: add example for upgrading a single package (#1500) | 2017-09-23T12:27:18 | [0d6202fa8981](https://github.com/tldr-pages/tldr/commit/0d6202fa8981b496d82fdd6d1704531262e9511e)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | Add `apt-get autoremove` (#1011) | 2016-08-22T00:01:13 | [63a7e2744e92](https://github.com/tldr-pages/tldr/commit/63a7e2744e92e5e121ebb413e97510ccd7b5ff47)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[Romain Prieto](mailto:rprieto@users.noreply.github.com) | Fix apt-get description (included back-ticks that confused some parsers) | 2014-10-01T13:12:34 | [e4f86136f6ee](https://github.com/tldr-pages/tldr/commit/e4f86136f6eece3536959a64e1b5eba300cfa307)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

