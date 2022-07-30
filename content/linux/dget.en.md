---
author: ['Lucas Gabriel Schneider', 'Pierre Rudloff']
date: 1612112718
title: "dget"
description: "dget, Download Debian packages."
categories: "linux"
---
> More information: <https://manpages.debian.org/dget>.

- Download a binary package:

```bash
dget package_name
```

- Download and extract a package source from its `.dsc` file:

```bash
dget http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc
```

- Download a package source tarball from its `.dsc` file but don't extract it:

```bash
dget -d http://deb.debian.org/debian/pool/main/h/haskell-tldr/haskell-tldr_0.4.0-2.dsc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Pierre Rudloff](mailto:contact@rudloff.pro) | debchange, debuild, dget, quilt: add pages (#4022) | 2020-05-14T17:07:23 | [20f4b567344a](https://github.com/tldr-pages/tldr/commit/20f4b567344aee07be76c6f6c440aef99cec69b3)

