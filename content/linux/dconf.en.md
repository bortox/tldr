---
author: ['Steven Pitts']
date: 1621187251
title: "dconf"
description: "dconf, Simple tool for manipulating dconf databases."
categories: "linux"
---
> See also `dconf write`.

> More information: <https://developer.gnome.org/dconf>.

- Print the value of a dconf path:

```bash
dconf read /example/dconf/path
```

- List contents of a dconf path:

```bash
dconf list /example/dconf/path
```

- Watch for dconf database changes in a path and subpaths:

```bash
dconf watch /example/dconf/path
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Steven Pitts](mailto:25968054+makusu2@users.noreply.github.com) | dconf, dconf-write: add page (#5967) | 2021-05-16T19:47:31 | [f82fd9c8f308](https://github.com/tldr-pages/tldr/commit/f82fd9c8f308c7eac988ff0c3e5df4968ef97914)

