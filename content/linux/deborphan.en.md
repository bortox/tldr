---
author: ['Pierre Rudloff']
date: 1634679688
title: "deborphan"
description: "deborphan, Display orphan packages on operating systems using the APT package manager."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/deborphan/deborphan.html>.

- Display library packages (from the "libs" section of the package repository) which are not required by another package:

```bash
deborphan
```

- List orphan packages from the "libs" section as well as orphan packages that have a name that looks like a library name:

```bash
deborphan --guess-all
```

- Find packages which are only recommended or suggested (but not required) by another package:

```bash
deborphan --nice-mode
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | deborphan: add page (#6921) | 2021-10-19T23:41:28 | [9a2cfc9e7dc5](https://github.com/tldr-pages/tldr/commit/9a2cfc9e7dc57336e5c7aa52448f7005e0fcbbfc)

