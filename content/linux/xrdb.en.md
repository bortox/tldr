---
author: ['Seth Falco']
date: 1632831809
title: "xrdb, TLDR Pages"
description: "xrdb, X window server's resource database utility for Unix-like systems."
categories: "linux"
---
> More information: <https://www.x.org/releases/X11R7.7/doc/man/man1/xrdb.1.xhtml>.

- Start `xrdb` in interactive mode:

```bash
xrdb
```

- Load values (e.g. style rules) from a resource file:

```bash
xrdb -load ~/.Xresources
```

- Query the resource database and print currently set values:

```bash
xrdb -query
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | xrdb: move to linux directory (#6606) | 2021-09-28T14:23:29 | [64d6a8ebfb47](https://github.com/tldr-pages/tldr/commit/64d6a8ebfb4761d9d7adfc9ccab35761ebf1102b)

