---
author: ['Tsvetomir Bonev']
date: 1633286882
title: "ego"
description: "ego, Funtoo's official system personality management tool."
categories: "linux"
---
> More information: <https://funtoo-ego.readthedocs.io/en/develop/>.

- Synchronize the Portage tree:

```bash
ego sync
```

- Update the bootloader configuration:

```bash
ego boot update
```

- Read a Funtoo wiki page by name:

```bash
ego doc wiki_page
```

- Print current profile:

```bash
ego profile show
```

- Enable/Disable mix-ins:

```bash
ego profile mix-in +gnome -kde-plasma-5
```

- Query Funtoo bugs, related to a specified package:

```bash
ego query bug package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tsvetomir Bonev](mailto:invakid404@riseup.net) | ego: add page (#6646) | 2021-10-03T20:48:02 | [ea63269e854d](https://github.com/tldr-pages/tldr/commit/ea63269e854d2b31773076f51f6b0c1159e7d985)

