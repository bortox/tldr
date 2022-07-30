---
author: ['bl-ue']
date: 1610056149
title: "git stripspace"
description: "git stripspace, Read text (e.g. commit messages, notes, tags, and branch descriptions) from the standard input and clean it into the manner used by Git."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-stripspace>.

- Trim whitespace from a file:

```bash
cat path/to/file | git stripspace
```

- Trim whitespace and Git comments from a file:

```bash
cat path/to/file | git stripspace --strip-comments
```

- Convert all lines in a file into Git comments:

```bash
git stripspace --comment-lines < path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-stripspace: add page (#5094) | 2021-01-07T22:49:09 | [db6ccdc929c6](https://github.com/tldr-pages/tldr/commit/db6ccdc929c6f57ea6f205221b61f2f0f8d959d7)

