---
author: ['bl-ue']
date: 1610197614
title: "git var"
description: "git var, Prints a Git logical variable's value."
categories: "common"
---
> See `git config`, which is preferred over `git var`.

> More information: <https://git-scm.com/docs/git-var>.

- Print the value of a Git logical variable:

```bash
git var GIT_AUTHOR_IDENT|GIT_COMMITTER_IDENT|GIT_EDITOR|GIT_PAGER
```

- [l]ist all Git logical variables:

```bash
git var -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-var: add page (#5095) * git-var: add page * Update pages/common/git-var.md Co-authored-by: Starbeamrainbowlabs [...] | 2021-01-09T14:06:54 | [2ee3968c441c](https://github.com/tldr-pages/tldr/commit/2ee3968c441cddd1b61a727cc30329ec27d6c63b)

