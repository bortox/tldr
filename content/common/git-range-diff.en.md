---
author: ['Janek']
date: 1622224887
title: "git range-diff, TLDR Pages"
description: "git range-diff, Compare two commit ranges (e.g. two versions of a branch)."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-range-diff>.

- Diff the changes of two individual commits:

```bash
git range-diff commit_1^! commit_2^!
```

- Diff the changes of ours and theirs from their common ancestor, e.g. after an interactive rebase:

```bash
git range-diff theirs...ours
```

- Diff the changes of two commit ranges, e.g. to check whether conflicts have been resolved appropriately when rebasing commits from `base1` to `base2`:

```bash
git range-diff base1..rev1 base2..rev2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Janek](mailto:27jf@pm.me) | git-range-diff: add page (#5701) | 2021-05-28T20:01:27 | [7aefc8588438](https://github.com/tldr-pages/tldr/commit/7aefc8588438fe27f355458934bcebf91b8a5897)

