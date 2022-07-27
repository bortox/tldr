---
author: ['Seth Falco']
date: 1653929852
title: "xdg-desktop-menu, TLDR Pages"
description: "xdg-desktop-menu, Command-line tool for installing or uninstalling desktop menu items."
categories: "linux"
---
> More information: <https://manned.org/xdg-desktop-menu>.

- Install an application to the desktop menu system:

```bash
xdg-desktop-menu install path/to/file.desktop
```

- Install an application to the desktop menu system with the vendor prefix check disabled:

```bash
xdg-desktop-menu install --novendor path/to/file.desktop
```

- Uninstall an application from the desktop menu system:

```bash
xdg-desktop-menu uninstall path/to/file.desktop
```

- Force an update of the desktop menu system:

```bash
xdg-desktop-menu forceupdate --mode user|system
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | xdg-desktop-menu: fix incorrectly documented command (#8112) | 2022-05-30T18:57:32 | [5d7574cb7419](https://github.com/tldr-pages/tldr/commit/5d7574cb741917e4203987f6a948402675ed47e4)
[Seth Falco](mailto:seth@falco.fun) | xdg-desktop-menu: add page (#8102) | 2022-05-22T17:02:24 | [17886acec8a5](https://github.com/tldr-pages/tldr/commit/17886acec8a5ab7fa753e43081954107ef0f2b19)

