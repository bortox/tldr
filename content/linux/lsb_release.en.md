---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'Ruben Vereecken']
date: 1629110041
title: "lsb_release"
description: "lsb_release, Provides certain LSB (Linux Standard Base) and distribution-specific information."
categories: "linux"
---
> More information: <https://manned.org/lsb_release>.

- Print all available information:

```bash
lsb_release -a
```

- Print a description (usually the full name) of the operating system:

```bash
lsb_release -d
```

- Print only the operating system name (ID), suppressing the field name:

```bash
lsb_release -i -s
```

- Print the release number and codename of the distribution, suppressing the field names:

```bash
lsb_release -rcs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Create lsb_release.md | 2015-10-09T10:17:32 | [c05879add2f4](https://github.com/tldr-pages/tldr/commit/c05879add2f4a19fa498484c75da0d8776b35bf6)

