---
author: ['Gingka Akiyama']
date: 1610673991
title: "dot_clean"
description: "dot_clean, Merge ._* files with corresponding native files."
categories: "osx"
---
> More information: <https://ss64.com/osx/dot_clean.html>.

- Merge all `._*` files recursively:

```bash
dot_clean path/to/directory
```

- Don't recursively merge all `._*` in a directory (flat merge):

```bash
dot_clean -f path/to/directory
```

- Merge and delete all `._*` files:

```bash
dot_clean -m path/to/directory
```

- Only delete `._*` files if there's a matching native file:

```bash
dot_clean -n path/to/directory
```

- Follow symlinks:

```bash
dot_clean -s path/to/directory
```

- Print verbose output:

```bash
dot_clean -v path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gingka Akiyama](mailto:33764485+GingkathFox@users.noreply.github.com) | dot_clean: add page (#5144) | 2021-01-15T02:26:31 | [2ef935200130](https://github.com/tldr-pages/tldr/commit/2ef935200130250e5020f39d0c91151d7d5f861f)

