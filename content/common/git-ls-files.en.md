---
author: ['Peder Bergebakken Sundt', 'Ehab Alsharif']
date: 1646189644
title: "git ls-files, TLDR Pages"
description: "git ls-files, Show information about files in the index and the working tree."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-ls-files>.

- Show deleted files:

```bash
git ls-files --deleted
```

- Show modified and deleted files:

```bash
git ls-files --modified
```

- Show ignored and untracked files:

```bash
git ls-files --others
```

- Show untracked files, not ignored:

```bash
git ls-files --others --exclude-standard
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peder Bergebakken Sundt](mailto:pbsds@hotmail.com) | Add command to git ls-files (#7833) Taken from https://fix.code-error.com/git-list-only-untracked-files-also-custom-commands/ | 2022-03-02T03:54:04 | [d774bbea9419](https://github.com/tldr-pages/tldr/commit/d774bbea9419fab873411af55bd6642cba2ef86c)
[Ehab Alsharif](mailto:36003641+sanehab@users.noreply.github.com) | git-ls-files: add page (#4753) | 2020-10-24T14:41:47 | [25adf84c0342](https://github.com/tldr-pages/tldr/commit/25adf84c03428969ff41d82c8d6c2f3744f1d2ea)

