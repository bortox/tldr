---
author: ['Puneetha Pai', 'lucas schneider']
date: 1610111394
title: "dvc diff, TLDR Pages"
description: "dvc diff, Show changes in DVC tracked file and directories."
categories: "common"
---
> More information: <https://dvc.org/doc/command-reference/diff>.

- Compare DVC tracked files from different Git commits, tags, and branches w.r.t the current workspace:

```bash
dvc diff commit_hash/tag/branch
```

- Compare the changes in DVC tracked files from 1 Git commit to another:

```bash
dvc diff revision_b revision_a
```

- Compare DVC tracked files, along with their latest hash:

```bash
dvc diff --show-hash commit
```

- Compare DVC tracked files, displaying the output as JSON:

```bash
dvc diff --show-json --show-hash commit
```

- Compare DVC tracked files, displaying the output as Markdown:

```bash
dvc diff --show-md --show-hash commit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | add missing pages | 2021-01-08T14:09:54 | [8d60f149451e](https://github.com/tldr-pages/tldr/commit/8d60f149451ebfc54332af0c2678732cc324d4e4)
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | dvc diff: Apply suggestions from code review Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-08-22T00:53:25 | [f45f4dafcb08](https://github.com/tldr-pages/tldr/commit/f45f4dafcb08e2a92fe9345ed9b2ce28ca40017b)
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | Apply suggestions from code review Thanks @sbrl. Will keep grammatical mistakes to minimum next time :smile Co-authored-by: [...] | 2020-08-22T00:53:25 | [91e565ba811e](https://github.com/tldr-pages/tldr/commit/91e565ba811e1112dc3e96f46d4b3d2bd96095c2)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: Fix failing tests | 2020-08-22T00:53:25 | [c6d6d7618c9b](https://github.com/tldr-pages/tldr/commit/c6d6d7618c9b9b6c480d485e8bacb9031cf817f9)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: add page including sub-commands destroy, diff and fetch | 2020-08-22T00:53:25 | [ca9b1f104ec0](https://github.com/tldr-pages/tldr/commit/ca9b1f104ec0c5f76981b07fd231996198fa97d6)

