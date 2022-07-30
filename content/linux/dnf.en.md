---
author: ['Andreas Schnebinger', 'Felix Yan', 'Christopher Doege', 'Onkar Ruikar', 'Konstantin A Kolosov', 'pixel', 'julienc91', 'jn64', 'Ruben Vereecken']
date: 1658077439
title: "dnf"
description: "dnf, Package management utility for RHEL, Fedora, and CentOS (replaces yum)."
categories: "linux"
---
> More information: <https://dnf.readthedocs.io>.

- Upgrade installed packages to the newest available versions:

```bash
sudo dnf upgrade
```

- Search packages via keywords:

```bash
dnf search keywords
```

- Display details about a package:

```bash
dnf info package
```

- Install a new package (use `-y` to confirm all prompts automatically):

```bash
sudo dnf install package
```

- Remove a package:

```bash
sudo dnf remove package
```

- List installed packages:

```bash
dnf list --installed
```

- Find which packages provide a given file:

```bash
dnf provides file
```

- View all past operations:

```bash
dnf history
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Onkar Ruikar](mailto:87750369+OnkarRuikar@users.noreply.github.com) | dnf: add history example (#8220) The history command shows well formatted installation log. Gives quick idea about what has happened [...] | 2022-07-17T19:03:59 | [160b91ce9594](https://github.com/tldr-pages/tldr/commit/160b91ce9594c41eb9ebaf764f03a231b76a4d71)
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[jn64](mailto:23169302+jn64@users.noreply.github.com) | dnf: add and reorder examples (#4063) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: Starbeamrainbowlabs [...] | 2020-05-28T14:07:09 | [c7ae6b3d8a75](https://github.com/tldr-pages/tldr/commit/c7ae6b3d8a75f4f313097690c0bc74baf5759d9d)
[Andreas Schnebinger](mailto:Iniesta8@users.noreply.github.com) | dnf: add examples (#3519) | 2019-11-11T15:42:06 | [a83040449e3a](https://github.com/tldr-pages/tldr/commit/a83040449e3ae0d66cb9964d5dfa566871b7ce6d)
[julienc91](mailto:github@julienc.io) | dnf: add sudo to examples | 2018-07-13T21:32:25 | [cd13678da0d6](https://github.com/tldr-pages/tldr/commit/cd13678da0d66a317e985fce7dc2d4a74e843121)
[julienc91](mailto:github@julienc.io) | dnf: removed update example | 2018-07-13T21:32:25 | [cfec692a273a](https://github.com/tldr-pages/tldr/commit/cfec692a273a259c80fab18c903121cb8dc116c7)
[Konstantin A Kolosov](mailto:konstantin.a.kolosov@gmail.com) | dnf: fix typo (#1121) Fedora was misspelled | 2016-10-17T23:46:16 | [1b8bf42af61c](https://github.com/tldr-pages/tldr/commit/1b8bf42af61c42da35a1f25480013398a38fc6cf)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Felix Yan](mailto:felixonmars@archlinux.org) | Remove trailing spaces for #476 | 2015-12-30T07:21:42 | [6e6ba15a89ee](https://github.com/tldr-pages/tldr/commit/6e6ba15a89ee8984cc8b2b1f90bcfcf1086ddd32)
[Christopher Doege](mailto:cdminigun@gmail.com) | Added dnf and yum to linux. Fixed wording. Small grammar change. Fixed capitalization. Fixed line spacing. | 2015-12-30T05:59:00 | [c21cba979b4a](https://github.com/tldr-pages/tldr/commit/c21cba979b4a0c4321250cece3f2bdaeedb22f2e)

