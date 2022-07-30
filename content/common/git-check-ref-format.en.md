---
author: ['bl-ue']
date: 1610017991
title: "git check-ref-format"
description: "git check-ref-format, Checks if a given refname is acceptable, and exits with a non-zero status if it is not."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-check-ref-format>.

- Check the format of the specified refname:

```bash
git check-ref-format refs/head/refname
```

- Print the name of the last branch checked out:

```bash
git check-ref-format --branch @{-1}
```

- Normalize a refname:

```bash
git check-ref-format --normalize refs/head/refname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-check-ref-format: add page (#5100) | 2021-01-07T12:13:11 | [7d6051e1ad92](https://github.com/tldr-pages/tldr/commit/7d6051e1ad9288abb01b6950bf25093ff71416b5)

