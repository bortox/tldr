---
author: ['Puneetha Pai']
date: 1598050405
title: "dvc dag, TLDR Pages"
description: "dvc dag, Visualize the pipeline(s) defined in `dvc.yaml`."
categories: "common"
---
> More information: <https://dvc.org/doc/command-reference/dag>.

- Visualize the entire pipeline:

```bash
dvc dag
```

- Visualize the pipeline stages up to a specified target stage:

```bash
dvc dag target
```

- Export the pipeline in the dot format:

```bash
dvc dag --dot > path/to/pipeline.dot
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Puneetha Pai](mailto:puneethapai29@gmail.com) | Resolve review comments which required edits and re-writes | 2020-08-22T00:53:25 | [12e2510f9982](https://github.com/tldr-pages/tldr/commit/12e2510f9982a355f10034f7c497b08938802db3)
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | Apply suggestions from code review Thanks @sbrl. Will keep grammatical mistakes to minimum next time :smile Co-authored-by: [...] | 2020-08-22T00:53:25 | [91e565ba811e](https://github.com/tldr-pages/tldr/commit/91e565ba811e1112dc3e96f46d4b3d2bd96095c2)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: Fix failing tests | 2020-08-22T00:53:25 | [c6d6d7618c9b](https://github.com/tldr-pages/tldr/commit/c6d6d7618c9b9b6c480d485e8bacb9031cf817f9)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: add pages for sub commands commit, config, dag | 2020-08-22T00:53:25 | [e94e07d26dc2](https://github.com/tldr-pages/tldr/commit/e94e07d26dc270c7a38086a7c69239ecdf1f97f7)

