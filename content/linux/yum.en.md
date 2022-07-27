---
author: ['Waldir Pimenta', 'Felix Yan', 'Joe Nichols', 'Christopher Doege', 'Ruben Vereecken', 'Andrea', 'Yi Ge', 'Daniel Zendejas', 'Seth Falco']
date: 1643127154
title: "yum, TLDR Pages"
description: "yum, Package management utility for RHEL, Fedora, and CentOS (for older versions)."
categories: "linux"
---
> More information: <https://manned.org/yum>.

- Install a new package:

```bash
yum install package
```

- Install a new package and assume yes to all questions (also works with update, great for automated updates):

```bash
yum -y install package
```

- Find the package that provides a particular command:

```bash
yum provides command
```

- Remove a package:

```bash
yum remove package
```

- Display available updates for installed packages:

```bash
yum check-update
```

- Upgrade installed packages to the newest available versions:

```bash
yum upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joe Nichols](mailto:GhostViz@users.noreply.github.com) | yum: use manned for more information link (#7708) | 2022-01-25T17:12:34 | [92343a1f94ac](https://github.com/tldr-pages/tldr/commit/92343a1f94ac280873c24487b3300bdd584039df)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Yi Ge](mailto:me@yige.ch) | yum: correct update command (#4708) | 2020-10-19T18:28:06 | [d8a1eabd934c](https://github.com/tldr-pages/tldr/commit/d8a1eabd934c97de8d33da78d50d4108a11cc919)
[Daniel Zendejas](mailto:daniel8647@hotmail.com) | yum: fix typo (#3845) | 2020-02-09T14:02:47 | [6ecb2a6d89bb](https://github.com/tldr-pages/tldr/commit/6ecb2a6d89bb17d537253569d56aaae6f0b090d6)
[Andrea](mailto:andrea-82@users.noreply.github.com) | yum: add "provides" example (#1132) "yum provides" is incredibly useful when you come from a different distro, and you don't know [...] | 2016-10-27T22:46:11 | [3df8a4b380d3](https://github.com/tldr-pages/tldr/commit/3df8a4b380d3d45a63d1c6fc2abf74e234ebf836)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | minor capitalization change | 2015-12-30T14:04:40 | [95fc5a0ef913](https://github.com/tldr-pages/tldr/commit/95fc5a0ef9135ca1edcaf6ea215156e83997381b)
[Felix Yan](mailto:felixonmars@archlinux.org) | Remove trailing spaces for #476 | 2015-12-30T07:21:42 | [6e6ba15a89ee](https://github.com/tldr-pages/tldr/commit/6e6ba15a89ee8984cc8b2b1f90bcfcf1086ddd32)
[Christopher Doege](mailto:cdminigun@gmail.com) | Added dnf and yum to linux. Fixed wording. Small grammar change. Fixed capitalization. Fixed line spacing. | 2015-12-30T05:59:00 | [c21cba979b4a](https://github.com/tldr-pages/tldr/commit/c21cba979b4a0c4321250cece3f2bdaeedb22f2e)

