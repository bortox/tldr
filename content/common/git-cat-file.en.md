---
author: ['Howard Yun', 'lucas schneider']
date: 1610111394
title: "git cat-file, TLDR Pages"
description: "git cat-file, Provide content or type and size information for Git repository objects."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-cat-file>.

- Get the [s]ize of the HEAD commit in bytes:

```bash
git cat-file -s HEAD
```

- Get the [t]ype (blob, tree, commit, tag) of a given Git object:

```bash
git cat-file -t 8c442dc3
```

- Pretty-[p]rint the contents of a given Git object based on its type:

```bash
git cat-file -p HEAD~2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Howard Yun](mailto:Haoy2001@gmail.com) | git-cat-file: add page (#4492) | 2020-10-05T16:55:53 | [53241532ce0b](https://github.com/tldr-pages/tldr/commit/53241532ce0bb38061d25d1f6d81ce450e75477e)

