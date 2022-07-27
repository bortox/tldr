---
author: ['bl-ue']
date: 1610906481
title: "git commit-graph, TLDR Pages"
description: "git commit-graph, Write and verify Git commit-graph files."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-commit-graph>.

- Write a commit-graph file for the packed commits in the repository's local `.git` directory:

```bash
git commit-graph write
```

- Write a commit-graph file containing all reachable commits:

```bash
git show-ref --hash | git commit-graph write --stdin-commits
```

- Write a commit-graph file containing all commits in the current commit-graph file along with those reachable from `HEAD`:

```bash
git rev-parse HEAD | git commit-graph write --stdin-commits --append
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-commit-graph: add page (#5109) | 2021-01-17T19:01:21 | [5a9ba8941517](https://github.com/tldr-pages/tldr/commit/5a9ba89415174e6b73a2584992ea92ebbdc2ffe8)

