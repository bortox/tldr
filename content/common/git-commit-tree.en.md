---
author: ['Lucas Gabriel Schneider', 'bl-ue']
date: 1612112718
title: "git commit-tree, TLDR Pages"
description: "git commit-tree, Low level utility to create commit objects."
categories: "common"
---
> See also: `git commit`.

> More information: <https://git-scm.com/docs/git-commit-tree>.

- Create a commit object with the specified message:

```bash
git commit-tree tree -m "message"
```

- Create a commit object reading the message from a file (use `-` for stdin):

```bash
git commit-tree tree -F path/to/file
```

- Create a GPG-signed commit object:

```bash
git commit-tree tree -m "message" --gpg-sign
```

- Create a commit object with the specified parent commit object:

```bash
git commit-tree tree -m "message" -p parent_commit_sha
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-commit-tree: add page (#5113) * git-commit-tree: add page * Update pages/common/git-commit-tree.md Co-authored-by: [...] | 2021-01-08T14:55:25 | [bae2dd054fdc](https://github.com/tldr-pages/tldr/commit/bae2dd054fdc96927cdf7decb7ace7365292c5c9)

