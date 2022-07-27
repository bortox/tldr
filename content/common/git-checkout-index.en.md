---
author: ['bl-ue']
date: 1610545196
title: "git checkout-index, TLDR Pages"
description: "git checkout-index, Copy files from the index to the working tree."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-checkout-index>.

- Restore any files deleted since the last commit:

```bash
git checkout-index --all
```

- Restore any files deleted or changed since the last commit:

```bash
git checkout-index --all --force
```

- Restore any files changed since the last commit, ignoring any files that were deleted:

```bash
git checkout-index --all --force --no-create
```

- Export a copy of the entire tree at the last commit to the specified directory (the trailing slash is important):

```bash
git checkout-index --all --force --prefix=path/to/export_directory/
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-checkout-index: add page (#5107) * git-checkout-index: add page * Update pages/common/git-checkout-index.md * Apply suggestions [...] | 2021-01-13T14:39:56 | [b9e4ed66d507](https://github.com/tldr-pages/tldr/commit/b9e4ed66d507afdba6c8fd2644e42ba79d6e9ee1)

