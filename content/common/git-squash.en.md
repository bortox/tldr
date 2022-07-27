---
author: ['Robson Cruz']
date: 1636372812
title: "git squash, TLDR Pages"
description: "git squash, Squash multiple commits into a single commit."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-squash>.

- Merge all commits from a specific branch into the current branch as a single commit:

```bash
git squash source_branch
```

- Squash all commits starting with a specific commit on the current branch:

```bash
git squash commit
```

- Squash the `n` latest commits and commit with a message:

```bash
git squash HEAD~n "message"
```

- Squash the `n` latest commits and commit concatenating all individual messages:

```bash
git squash --squash-msg HEAD~n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Robson Cruz](mailto:deadpyxel@users.noreply.github.com) | git-squash: add page (#7361) | 2021-11-08T13:00:12 | [7030c6178606](https://github.com/tldr-pages/tldr/commit/7030c617860610461dbdf7665e480c44d10f8989)

