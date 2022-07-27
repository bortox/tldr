---
author: ['Peter Babič']
date: 1640624108
title: "git filter-repo, TLDR Pages"
description: "git filter-repo, A versatile tool for rewriting Git history."
categories: "common"
---
> See also: `bfg`.

> More information: <https://github.com/newren/git-filter-repo>.

- Replace a sensitive string in all files:

```bash
git filter-repo --replace-text <(echo 'find==>replacement')
```

- Extract a single folder, keeping history:

```bash
git-filter-repo --path path/to/folder
```

- Remove a single folder, keeping history:

```bash
git-filter-repo --path path/to/folder --invert-paths
```

- Move everything from sub-folder one level up:

```bash
git-filter-repo --path-rename path/to/folder/:
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@babic.dev) | git-filter-repo: add page (#7493) | 2021-12-27T17:55:08 | [d7375910c783](https://github.com/tldr-pages/tldr/commit/d7375910c7838c4f425dea8277e8783322d49c41)

