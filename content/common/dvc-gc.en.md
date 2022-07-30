---
author: ['Puneetha Pai']
date: 1598050405
title: "dvc gc"
description: "dvc gc, Remove unused files and directories from the cache or remote storage."
categories: "common"
---
> More information: <https://dvc.org/doc/command-reference/gc>.

- Garbage collect from the cache, keeping only versions referenced by the current workspace:

```bash
dvc gc --workspace
```

- Garbage collect from the cache, keeping only versions referenced by branch, tags, and commits:

```bash
dvc gc --all-branches --all-tags --all-commits
```

- Garbage collect from the cache, including the default cloud remote storage (if set):

```bash
dvc gc --all-commits --cloud
```

- Garbage collect from the cache, including a specific cloud remote storage:

```bash
dvc gc --all-commits --cloud --remote remote_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Puneetha Pai](mailto:puneethapai29@gmail.com) | Resolve review comments which required edits and re-writes | 2020-08-22T00:53:25 | [12e2510f9982](https://github.com/tldr-pages/tldr/commit/12e2510f9982a355f10034f7c497b08938802db3)
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | Apply suggestions from code review Thanks @sbrl. Will keep grammatical mistakes to minimum next time :smile Co-authored-by: [...] | 2020-08-22T00:53:25 | [91e565ba811e](https://github.com/tldr-pages/tldr/commit/91e565ba811e1112dc3e96f46d4b3d2bd96095c2)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: add page including sub-commands freeze, unfreeze and gc | 2020-08-22T00:53:25 | [c96d68ed62ab](https://github.com/tldr-pages/tldr/commit/c96d68ed62ab4c5ec822fb68cf1a3ebf9aee5199)

