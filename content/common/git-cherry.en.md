---
author: ['Amory Meltzer']
date: 1602099635
title: "git cherry"
description: "git cherry, Find commits that have yet to be applied upstream."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-cherry>.

- Show commits (and their messages) with equivalent commits upstream:

```bash
git cherry -v
```

- Specify a different upstream and topic branch:

```bash
git cherry origin topic
```

- Limit commits to those within a given limit:

```bash
git cherry origin topic base
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Amory Meltzer](mailto:Amorymeltzer@gmail.com) | git-cherry: add page (#4473) | 2020-10-07T21:40:35 | [352c86363844](https://github.com/tldr-pages/tldr/commit/352c86363844d93640edb5eba824d64b8cf7fb44)

