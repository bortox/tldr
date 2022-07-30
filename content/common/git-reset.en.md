---
author: ['Waldir Pimenta', 'lucas schneider', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Eliot Sykes', 'marchersimon']
date: 1622201439
title: "git reset"
description: "git reset, Undo commits or unstage changes, by resetting the current Git HEAD to the specified state."
categories: "common"
---
> If a path is passed, it works as "unstage"; if a commit hash or branch is passed, it works as "uncommit".

> More information: <https://git-scm.com/docs/git-reset>.

- Unstage everything:

```bash
git reset
```

- Unstage specific file(s):

```bash
git reset path/to/file(s)
```

- Interactively unstage portions of a file:

```bash
git reset --patch path/to/file
```

- Undo the last commit, keeping its changes (and any further uncommitted changes) in the filesystem:

```bash
git reset HEAD~
```

- Undo the last two commits, adding their changes to the index, i.e. staged for commit:

```bash
git reset --soft HEAD~2
```

- Discard any uncommitted changes, staged or not (for only unstaged changes, use `git checkout`):

```bash
git reset --hard
```

- Reset the repository to a given commit, discarding committed, staged and uncommitted changes since then:

```bash
git reset --hard commit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | git-reset: clarify patch example and use long option (#6006) | 2021-05-28T13:30:39 | [9fe15f560944](https://github.com/tldr-pages/tldr/commit/9fe15f560944e421629b70d2e1979f65a569036b)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-reset: add simpler --hard example | 2017-05-18T18:25:09 | [595c4eb2341b](https://github.com/tldr-pages/tldr/commit/595c4eb2341baa97902a9f5407ec09da75182c4e)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-reset: expand page (#1127) As mentioned in https://github.com/tldr-pages/tldr/pull/1088#issuecomment-249368792 | 2016-10-27T19:27:41 | [05c63936ce7d](https://github.com/tldr-pages/tldr/commit/05c63936ce7d26049238802ccf1ca194cfd11b40)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | git-reset: add page (#1088) | 2016-09-26T19:49:39 | [26700bf198ae](https://github.com/tldr-pages/tldr/commit/26700bf198ae41f0f010f8947e38472febb82014)

