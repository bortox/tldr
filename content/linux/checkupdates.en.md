---
author: ['Axel Navarro']
date: 1645091820
title: "checkupdates, TLDR Pages"
description: "checkupdates, Tool to check pending updates in Arch Linux."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/checkupdates.8>.

- List pending updates:

```bash
checkupdates
```

- List pending updates and download the packages to the pacman cache:

```bash
checkupdates --download
```

- List pending updates using a specific pacman database:

```bash
CHECKUPDATES_DB=path/to/directory checkupdates
```

- Display help:

```bash
checkupdates --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | checkupdates: add page (#7774) | 2022-02-17T10:57:00 | [45f7d2751200](https://github.com/tldr-pages/tldr/commit/45f7d2751200f9ba5b2859b03f49c0841c81279c)

