---
author: ['Managor']
date: 1636334743
title: "pactree"
description: "pactree, Package dependency tree viewer for pacman."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pactree.8>.

- Print the dependency tree of a specific package:

```bash
pactree package
```

- Print what packages depend on a specific package:

```bash
pactree --reverse package
```

- Dump dependencies one per line, skipping duplicates:

```bash
pactree --unique package
```

- Include optional dependencies of a specific package and colorize the output:

```bash
pactree --optional --color package
```

- Display help:

```bash
pactree
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | pactree: add page (#7326) | 2021-11-08T02:25:43 | [7a917bda000f](https://github.com/tldr-pages/tldr/commit/7a917bda000f61a99d6f80b7bd0293df9be4b19e)

