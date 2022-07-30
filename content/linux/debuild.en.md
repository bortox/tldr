---
author: ['Pierre Rudloff']
date: 1589468843
title: "debuild"
description: "debuild, Tool to build a Debian package from source."
categories: "linux"
---
> More information: <https://manpages.debian.org/debuild>.

- Build the package in the current directory:

```bash
debuild
```

- Build a binary package only:

```bash
debuild -b
```

- Do not run lintian after building the package:

```bash
debuild --no-lintian
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | debchange, debuild, dget, quilt: add pages (#4022) | 2020-05-14T17:07:23 | [20f4b567344a](https://github.com/tldr-pages/tldr/commit/20f4b567344aee07be76c6f6c440aef99cec69b3)

