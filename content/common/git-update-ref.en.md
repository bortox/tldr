---
author: ['Ehab Alsharif', 'lucas schneider']
date: 1610111394
title: "git update-ref"
description: "git update-ref, Git command for creating, updating, and deleting Git refs."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-update-ref>.

- Delete a ref, useful for soft resetting the first commit:

```bash
git update-ref -d HEAD
```

- Update ref with a message:

```bash
git update-ref -m message HEAD 4e95e05
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Ehab Alsharif](mailto:36003641+sanehab@users.noreply.github.com) | git-update-ref: add page (#4373) | 2020-10-01T20:58:34 | [79aea4833f7a](https://github.com/tldr-pages/tldr/commit/79aea4833f7a10fc789963166b34a98ed7b69f1b)

