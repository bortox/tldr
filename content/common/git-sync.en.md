---
author: ['Robson Cruz']
date: 1636245072
title: "git sync"
description: "git sync, Sync local branches with remote branches."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-sync>.

- Sync the current local branch with its remote branch:

```bash
git sync
```

- Sync the current local branch with the remote main branch:

```bash
git sync origin main
```

- Sync without cleaning untracked files:

```bash
git sync -s remote_name branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Robson Cruz](mailto:deadpyxel@users.noreply.github.com) | git-sync: add page (#7357) | 2021-11-07T01:31:12 | [e110428da7aa](https://github.com/tldr-pages/tldr/commit/e110428da7aa21be2a74f4b4b1cef5a66b659adf)

