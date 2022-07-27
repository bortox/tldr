---
author: ['Steve Robillard']
date: 1633879872
title: "checkinstall, TLDR Pages"
description: "checkinstall, Track the local installation of a software package, and produce a binary package which can be used with a system's native package manager."
categories: "linux"
---
> More information: <http://checkinstall.izto.org>.

- Create and install a package with default settings:

```bash
sudo checkinstall --default
```

- Create a package but don't install it:

```bash
sudo checkinstall --install=no
```

- Create a package without documentation:

```bash
sudo checkinstall --nodoc
```

- Create a package and set the name:

```bash
sudo checkinstall --pkgname package
```

- Create a package and specify where to save it:

```bash
sudo checkinstall --pakdir path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Steve Robillard](mailto:steverobillard@gmail.com) | checkinstall: add page (#6916) | 2021-10-10T17:31:12 | [db163c6b7847](https://github.com/tldr-pages/tldr/commit/db163c6b784731b9396320a5a7f32713f519658e)

