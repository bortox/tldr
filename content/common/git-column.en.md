---
author: ['bl-ue']
date: 1610091226
title: "git column"
description: "git column, Display data in columns."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-column>.

- Format the standard input as multiple columns:

```bash
ls | git column --mode=column
```

- Format the standard input as multiple columns with a maximum width of `100`:

```bash
ls | git column --mode=column --width=100
```

- Format the standard input as multiple columns with a maximum padding of `30`:

```bash
ls | git column --mode=column --padding=30
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-column: add page (#5108) | 2021-01-08T08:33:46 | [b57f62cb20d9](https://github.com/tldr-pages/tldr/commit/b57f62cb20d963f412cd814483947e770c8d2a6f)

