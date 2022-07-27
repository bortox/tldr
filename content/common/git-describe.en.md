---
author: ['Antoine Amara', 'Seth Falco', 'lucas schneider']
date: 1629050349
title: "git describe, TLDR Pages"
description: "git describe, Give an object a human-readable name based on an available ref."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-describe>.

- Create a unique name for the current commit (the name contains the most recent annotated tag, the number of additional commits, and the abbreviated commit hash):

```bash
git describe
```

- Create a name with 4 digits for the abbreviated commit hash:

```bash
git describe --abbrev=4
```

- Generate a name with the tag reference path:

```bash
git describe --all
```

- Describe a Git tag:

```bash
git describe v1.0.0
```

- Create a name for the last commit of a given branch:

```bash
git describe branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Antoine Amara](mailto:amara.antoine@gmail.com) | git-describe: add page (#4413) | 2020-10-05T16:30:10 | [720939426a8a](https://github.com/tldr-pages/tldr/commit/720939426a8a3b4bf0131115900c8467f4aa86ef)

