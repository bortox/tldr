---
author: ['CleanMachine1']
date: 1643667917
title: "git standup, TLDR Pages"
description: "git standup, See commits from a specified user."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-standup>.

- Show a given author's commits from the last 10 days:

```bash
git standup -a name|email -d 10
```

- Show a given author's commits from the last 10 days and whether they are GPG signed:

```bash
git standup -a {[name|email -d 10 -g
```

- Show all the commits from all contributors for the last 10 days:

```bash
git standup -a all -d 10
```

- Display help:

```bash
git standup -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | git-standup: add page (#7584) * git-standup: add page * Update pages/common/git-standup.md Co-authored-by: Axel Navarro [...] | 2022-01-31T23:25:17 | [02a843bea81c](https://github.com/tldr-pages/tldr/commit/02a843bea81c14afc56a33e3f0369a54ac83a70b)

