---
author: ['Ishank Sharma']
date: 1612034916
title: "gdebi, TLDR Pages"
description: "gdebi, Simple tool to install `.deb` files."
categories: "linux"
---
> More information: <https://www.commandlinux.com/man-page/man1/gdebi.1.html>.

- Install local `.deb` packages resolving and installing its dependencies:

```bash
gdebi path/to/package.deb
```

- Display the program version:

```bash
gdebi --version
```

- Do not show progress information:

```bash
gdebi path/to/package.deb --quiet
```

- Set an APT configuration option:

```bash
gdebi path/to/package.deb --option=APT_OPTS
```

- Use alternative root dir:

```bash
gdebi path/to/package.deb --root=path/to/root_dir
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ishank Sharma](mailto:ishank.web.dev@gmail.com) | gdebi: add page (#5204) | 2021-01-30T20:28:36 | [2280a5a6a234](https://github.com/tldr-pages/tldr/commit/2280a5a6a234cbcd6e89a7c2871d5ef373daaf8d)

