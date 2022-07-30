---
author: ['Thomas Wünsche', 'bl-ue', 'Starbeamrainbowlabs', 'lucas schneider']
date: 1610124748
title: "git restore"
description: "git restore, Restore working tree files. Requires Git version 2.23+."
categories: "common"
---
> See also `git checkout` and `git reset`.

> More information: <https://git-scm.com/docs/git-restore>.

- Restore an unstaged file to the version of the current commit (HEAD):

```bash
git restore path/to/file
```

- Restore an unstaged file to the version of a specific commit:

```bash
git restore --source commit path/to/file
```

- Discard all unstaged changes to tracked files:

```bash
git restore :/
```

- Unstage a file:

```bash
git restore --staged path/to/file
```

- Unstage all files:

```bash
git restore --staged :/
```

- Discard all changes to files, both staged and unstaged:

```bash
git restore --worktree --staged :/
```

- Interactively select sections of files to restore:

```bash
git restore --patch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-restore: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [0263149af3d6](https://github.com/tldr-pages/tldr/commit/0263149af3d6de47b9741be4daadb0b819d1415b)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Thomas Wünsche](mailto:42999314+thomaswuensche@users.noreply.github.com) | git-restore: add examples (#5101) * git-restore: add examples * update git-restore.md Co-authored-by: Starbeamrainbowlabs [...] | 2021-01-07T13:58:00 | [d157c1f373c9](https://github.com/tldr-pages/tldr/commit/d157c1f373c92ce70df7455ac0ab151c47022639)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | git-restore: add page (#3247) | 2019-08-23T19:22:38 | [22dc13a4085a](https://github.com/tldr-pages/tldr/commit/22dc13a4085a24d41f350def1057c7f1a1f81b3e)

