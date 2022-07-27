---
author: ['Ehab Alsharif', 'Lucas Gabriel Schneider', 'bl-ue', 'lucas schneider']
date: 1612112718
title: "git prune, TLDR Pages"
description: "git prune, Git command for pruning all unreachable objects from the object database."
categories: "common"
---
> This command is often not used directly but as an internal command that is used by Git gc.

> More information: <https://git-scm.com/docs/git-prune>.

- Report what would be removed by Git prune without removing it:

```bash
git prune --dry-run
```

- Prune unreachable objects and display what has been pruned to stdout:

```bash
git prune --verbose
```

- Prune unreachable objects while showing progress:

```bash
git prune --progress
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Ehab Alsharif](mailto:36003641+sanehab@users.noreply.github.com) | git-prune: add page (#4696) | 2020-10-16T10:53:07 | [fd7109217683](https://github.com/tldr-pages/tldr/commit/fd7109217683a9d874093ace275ede78c3512d0f)

