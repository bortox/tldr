---
author: ['Marco Bonelli', 'pxgamer', 'Owen Voke']
date: 1559564381
title: "hg log, TLDR Pages"
description: "hg log, Display the revision history of the repository."
categories: "common"
---
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#log>.

- Display the entire revision history of the repository:

```bash
hg log
```

- Display the revision history with an ASCII graph:

```bash
hg log --graph
```

- Display the revision history with file names matching a specified pattern:

```bash
hg log --include pattern
```

- Display the revision history, excluding file names that match a specified pattern:

```bash
hg log --exclude pattern
```

- Display the log information for a specific revision:

```bash
hg log --rev revision
```

- Display the revision history for a specific branch:

```bash
hg log --branch branch
```

- Display the revision history for a specific date:

```bash
hg log --date date
```

- Display revisions committed by a specific user:

```bash
hg log --user user
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | hg-log: add link to homepage | 2019-03-24T00:27:35 | [f6e007764e1e](https://github.com/tldr-pages/tldr/commit/f6e007764e1ea77ba5c63442ba82bcac5e05a05c)
[Owen Voke](mailto:owzie123@gmail.com) | hg-log: add page (#1879) | 2018-01-18T08:15:11 | [01be8e6f47da](https://github.com/tldr-pages/tldr/commit/01be8e6f47da1a43fc9836e44d6ed51d8e65e640)

