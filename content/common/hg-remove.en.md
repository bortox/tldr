---
author: ['Marco Bonelli', 'pxgamer', 'Owen Voke']
date: 1559564381
title: "hg remove, TLDR Pages"
description: "hg remove, Remove specified files from the staging area."
categories: "common"
---
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#remove>.

- Remove files or directories from the staging area:

```bash
hg remove path/to/file
```

- Remove all staged files matching a specified pattern:

```bash
hg remove --include pattern
```

- Remove all staged files, excluding those that match a specified pattern:

```bash
hg remove --exclude pattern
```

- Recursively remove sub-repositories:

```bash
hg remove --subrepos
```

- Remove files from the repository that have been physically removed:

```bash
hg remove --after
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | hg-remove: add link to homepage | 2019-03-24T00:27:35 | [af14d2e45980](https://github.com/tldr-pages/tldr/commit/af14d2e4598018b96080e8ac3fe8331c74a82b71)
[Owen Voke](mailto:owzie123@gmail.com) | hg-remove: add page (#1859) | 2018-01-09T20:51:46 | [c1d30cf8eac2](https://github.com/tldr-pages/tldr/commit/c1d30cf8eac200010eeb3981c9e4125d2296d18d)

