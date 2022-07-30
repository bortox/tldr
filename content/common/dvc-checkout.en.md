---
author: ['Seth Falco', 'Puneetha Pai']
date: 1629050349
title: "dvc checkout"
description: "dvc checkout, Checkout data files and directories from cache."
categories: "common"
---
> More information: <https://dvc.org/doc/command-reference/checkout>.

- Checkout the latest version of all target files and directories:

```bash
dvc checkout
```

- Checkout the latest version of a specified target:

```bash
dvc checkout target
```

- Checkout a specific version of a target from a different Git commit/tag/branch:

```bash
git checkout commit_hash|tag|branch target && dvc checkout target
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | Resolve review comments which required edits and re-writes | 2020-08-22T00:53:25 | [12e2510f9982](https://github.com/tldr-pages/tldr/commit/12e2510f9982a355f10034f7c497b08938802db3)
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | Apply suggestions from code review Thanks @sbrl. Will keep grammatical mistakes to minimum next time :smile Co-authored-by: [...] | 2020-08-22T00:53:25 | [91e565ba811e](https://github.com/tldr-pages/tldr/commit/91e565ba811e1112dc3e96f46d4b3d2bd96095c2)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: add page including sub-commands checkout, init, add | 2020-08-22T00:53:25 | [51190d4610d7](https://github.com/tldr-pages/tldr/commit/51190d4610d79700de85ecfdf12b61be6a70b28a)

