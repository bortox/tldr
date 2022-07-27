---
author: ['Seth Falco']
date: 1622804746
title: "qtchooser, TLDR Pages"
description: "qtchooser, A wrapper used to select between Qt development binary versions."
categories: "linux"
---
> More information: <https://manned.org/qtchooser>.

- List available Qt versions from the configuration files:

```bash
qtchooser --list-versions
```

- Print environment information:

```bash
qtchooser --print-env
```

- Run the specified tool using the specified Qt version:

```bash
qtchooser --run-tool=tool --qt=version_name
```

- Add a Qt version entry to be able to choose from:

```bash
qtchooser --install version_name path/to/qmake
```

- Display all available options:

```bash
qtchooser --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | qtchooser: add page (#6079) | 2021-06-04T13:05:46 | [8f85a31e632d](https://github.com/tldr-pages/tldr/commit/8f85a31e632ddddb1f9630a254396af5777ca2d5)

