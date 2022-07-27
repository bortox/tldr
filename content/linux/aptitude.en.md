---
author: ['Patrice Denis', 'lord63', 'Junjue Wang', '85pando', 'Ruben Vereecken', 'Gubolin', 'Darexon', 'Seth Falco']
date: 1629050349
title: "aptitude, TLDR Pages"
description: "aptitude, Debian and Ubuntu package management utility."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Synchronize list of packages and versions available. This should be run first, before running subsequent aptitude commands:

```bash
aptitude update
```

- Install a new package and its dependencies:

```bash
aptitude install package
```

- Search for a package:

```bash
aptitude search package
```

- Search for an installed package (`?installed` is an aptitude search term):

```bash
aptitude search '?installed(package)'
```

- Remove a package and all packages depending on it:

```bash
aptitude remove package
```

- Upgrade installed packages to the newest available versions:

```bash
aptitude upgrade
```

- Upgrade installed packages (like `aptitude upgrade`) including removing obsolete packages and installing additional packages to meet new package dependencies:

```bash
aptitude full-upgrade
```

- Put an installed package on hold to prevent it from being automatically upgraded:

```bash
aptitude hold '?installed(package)'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Junjue Wang](mailto:junjuew@cs.cmu.edu) | aptitude: add search term and hold examples (#3380) | 2019-10-13T13:15:33 | [d5a58cba9dee](https://github.com/tldr-pages/tldr/commit/d5a58cba9dee726dfcce715e05d3d60e45134d50)
[Darexon](mailto:darexon331@gmail.com) | aptitude: remove purge | 2017-10-20T18:40:40 | [9a0703c3be32](https://github.com/tldr-pages/tldr/commit/9a0703c3be326a252c3d06765ae40b08c650cdaf)
[85pando](mailto:85pando@googlemail.com) | Update aptitude.md: purge command + better desc * `aptitude install {{package}}` also installs dependencies. * `aptitude remove [...] | 2016-01-31T09:44:21 | [03da0de396f8](https://github.com/tldr-pages/tldr/commit/03da0de396f8bd16a4529672951cb7a7172bc55a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[Gubolin](mailto:gubolin@fantasymail.de) | aptitude.md | 2014-03-05T16:53:06 | [1825a422a805](https://github.com/tldr-pages/tldr/commit/1825a422a8052d5a0ebfa0c02def950d727e3885)

