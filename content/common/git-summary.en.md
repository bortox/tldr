---
author: ['CleanMachine1', 'a1346054']
date: 1631763133
title: "git summary, TLDR Pages"
description: "git summary, Display information about a Git repository."
categories: "common"
---
> Part of `git-extras`.

> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-summary>.

- Display data about a Git repository:

```bash
git summary
```

- Display data about a Git repository since a commit-ish:

```bash
git summary commit|branch_name|tag_name
```

- Display data about a Git repository, merging committers using different emails into 1 statistic for each author:

```bash
git summary --dedup-by-email
```

- Display data about a Git repository, showing the number of lines modified by each contributor:

```bash
git summary --line
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[a1346054](mailto:36859588+a1346054@users.noreply.github.com) | *: shellcheck and fix typos (#6526) * test.sh: quote a variable * contributing-guides/*: fix typos * pages/*: fix typos * scripts/*: [...] | 2021-09-16T05:32:13 | [5c62e303b5ab](https://github.com/tldr-pages/tldr/commit/5c62e303b5ab7c0f38b360c3918380ccd011a536)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | git-summary: add page (#6065) | 2021-06-07T22:03:11 | [4272859c5b1d](https://github.com/tldr-pages/tldr/commit/4272859c5b1d5cf66b4d39f559e1dbfc929fa848)

