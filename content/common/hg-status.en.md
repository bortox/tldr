---
author: ['Owen Voke', 'Marco Bonelli']
date: 1559564381
title: "hg status"
description: "hg status, Show files that have changed in the working directory."
categories: "common"
---
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#status>.

- Display the status of changed files:

```bash
hg status
```

- Display only modified files:

```bash
hg status --modified
```

- Display only added files:

```bash
hg status --added
```

- Display only removed files:

```bash
hg status --removed
```

- Display only deleted (but tracked) files:

```bash
hg status --deleted
```

- Display changes in the working directory compared to a specified changeset:

```bash
hg status --rev revision
```

- Display only files matching a specified glob pattern:

```bash
hg status --include pattern
```

- Display files, excluding those that match a specified glob pattern:

```bash
hg status --exclude pattern
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | hg-status: add page (#2847) | 2019-03-26T11:20:30 | [ad348f3ee137](https://github.com/tldr-pages/tldr/commit/ad348f3ee137241694763cfe0e59fed6a3c72508)

