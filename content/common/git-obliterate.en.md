---
author: ['CleanMachine1']
date: 1623421161
title: "git obliterate"
description: "git obliterate, Delete specific files and erase their history from a Git repository."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-obliterate>.

- Erase the existence of specific files:

```bash
git obliterate file_1 file_2 ...
```

- Erase the existence of specific files between 2 commits:

```bash
git obliterate file_1 file_2 ... -- commit_hash_1..commit_hash_2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | git-obliterate: add page (#6099) | 2021-06-11T16:19:21 | [427911afd364](https://github.com/tldr-pages/tldr/commit/427911afd364f7b9bb6c63a602f1c18881272bd9)

