---
author: ['nav1s']
date: 1634123753
title: "git reauthor, TLDR Pages"
description: "git reauthor, Change details about an author identity. Since this command rewrites the Git history, `--force` will be needed when pushing next time."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-reauthor>.

- Change an author's email and name across the whole Git repository:

```bash
git reauthor --old-email old@example.com --correct-email new@example.com --correct-name "name"
```

- Change the email and name to the ones defined in the Git config:

```bash
git reauthor --old-email old@example.com --use-config
```

- Change the email and name of all commits, regardless of their original author:

```bash
git reauthor --all --correct-email name@example.com --correct-name name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nav1s](mailto:42621369+nav1s@users.noreply.github.com) | git-reauthor: add page (#6651) | 2021-10-13T13:15:53 | [0a51a8c86c51](https://github.com/tldr-pages/tldr/commit/0a51a8c86c51b2ae869d1cabd18532ade441389d)

