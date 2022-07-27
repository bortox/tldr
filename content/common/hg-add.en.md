---
author: ['Marco Bonelli', 'pxgamer', 'Owen Voke']
date: 1559564381
title: "hg add, TLDR Pages"
description: "hg add, Adds specified files to the staging area for the next commit in Mercurial."
categories: "common"
---
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#add>.

- Add files or directories to the staging area:

```bash
hg add path/to/file
```

- Add all unstaged files matching a specified pattern:

```bash
hg add --include pattern
```

- Add all unstaged files, excluding those that match a specified pattern:

```bash
hg add --exclude pattern
```

- Recursively add sub-repositories:

```bash
hg add --subrepos
```

- Perform a test-run without performing any actions:

```bash
hg add --dry-run
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | hg-add: add link to homepage | 2019-03-24T00:27:35 | [984ccacaff66](https://github.com/tldr-pages/tldr/commit/984ccacaff66e1b137ecdf62c0e8ab8f17896110)
[Owen Voke](mailto:owzie123@gmail.com) | hg-add: add page (#1789) | 2017-12-14T06:22:24 | [fcd411eafcc1](https://github.com/tldr-pages/tldr/commit/fcd411eafcc1884b59db9466df4ec4752b5bc967)

