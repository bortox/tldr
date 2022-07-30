---
author: ['Puneetha Pai']
date: 1598050405
title: "dvc fetch"
description: "dvc fetch, Download DVC tracked files and directories from a remote repository."
categories: "common"
---
> More information: <https://dvc.org/doc/command-reference/fetch>.

- Fetch the latest changes from the default remote upstream repository (if set):

```bash
dvc fetch
```

- Fetch changes from a specific remote upstream repository:

```bash
dvc fetch --remote remote_name
```

- Fetch the latest changes for a specific target/s:

```bash
dvc fetch target/s
```

- Fetch changes for all branch and tags:

```bash
dvc fetch --all-branches --all-tags
```

- Fetch changes for all commits:

```bash
dvc fetch --all-commits
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: add page including sub-commands destroy, diff and fetch | 2020-08-22T00:53:25 | [ca9b1f104ec0](https://github.com/tldr-pages/tldr/commit/ca9b1f104ec0c5f76981b07fd231996198fa97d6)

