---
author: ['nath1as']
date: 1602299637
title: "legit, TLDR Pages"
description: "legit, Complementary command-line interface for Git."
categories: "linux"
---
> More information: <https://frostming.github.io/legit>.

- Switch to a specified branch, stashing and restoring unstaged changes:

```bash
git switch target_branch
```

- Synchronize current branch, automatically merging or rebasing, and stashing and unstashing:

```bash
git sync
```

- Publish a specified branch to the remote server:

```bash
git publish branch_name
```

- Remove a branch from the remote server:

```bash
git unpublish branch_name
```

- List all branches and their publication status:

```bash
git branches glob_pattern
```

- Remove the last commit from the history:

```bash
git undo --hard
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nath1as](mailto:n@th1.as) | legit: add page (#4425) | 2020-10-10T05:13:57 | [be42a2feeaa6](https://github.com/tldr-pages/tldr/commit/be42a2feeaa6a2216bc5adf5f63d65e35475559c)

