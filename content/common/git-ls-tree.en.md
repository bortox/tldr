---
author: ['Valentin Vetter']
date: 1576614677
title: "git ls-tree"
description: "git ls-tree, List the contents of a tree object."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-ls-tree>.

- List the contents of the tree on a branch:

```bash
git ls-tree branch_name
```

- List the contents of the tree on a commit, recursing into subtrees:

```bash
git ls-tree -r commit_hash
```

- List only the filenames of the tree on a commit:

```bash
git ls-tree --name-only commit_hash
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Valentin Vetter](mailto:BeLi4L@users.noreply.github.com) | git-ls-tree, git-rev-list, git-rev-parse: add pages (#3644) | 2019-12-17T21:31:17 | [a1a3faecb846](https://github.com/tldr-pages/tldr/commit/a1a3faecb846d3beb25615475818b4f5beafeb32)

