---
author: ['Puneetha Pai']
date: 1598050405
title: "dvc add"
description: "dvc add, Add changed files to the index."
categories: "common"
---
> More information: <https://dvc.org/doc/command-reference/add>.

- Add a single target file to the index:

```bash
dvc add path/to/file
```

- Add a target directory to the index:

```bash
dvc add path/to/directory
```

- Recursively add all the files in a given target directory:

```bash
dvc add --recursive path/to/directory
```

- Add a target file with a custom `.dvc` filename:

```bash
dvc add --file custom_name.dvc path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | Apply suggestions from code review by @einverne Co-authored-by: Ein Verne <git@einverne.info> | 2020-08-22T00:53:25 | [a398529a92ea](https://github.com/tldr-pages/tldr/commit/a398529a92ea7e4f58c4da1ad807f0878d8ae880)
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | Apply suggestions from code review Thanks @sbrl. Will keep grammatical mistakes to minimum next time :smile Co-authored-by: [...] | 2020-08-22T00:53:25 | [91e565ba811e](https://github.com/tldr-pages/tldr/commit/91e565ba811e1112dc3e96f46d4b3d2bd96095c2)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: Fix failing tests | 2020-08-22T00:53:25 | [c6d6d7618c9b](https://github.com/tldr-pages/tldr/commit/c6d6d7618c9b9b6c480d485e8bacb9031cf817f9)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: add page including sub-commands checkout, init, add | 2020-08-22T00:53:25 | [51190d4610d7](https://github.com/tldr-pages/tldr/commit/51190d4610d79700de85ecfdf12b61be6a70b28a)

