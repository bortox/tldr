---
author: ['Waldir Pimenta', 'lucas schneider', 'Casper Hollingberry', 'kxy', 'Axel Navarro', 'lord63', 'markevan100', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Eliot Sykes', 'Ruben Vereecken', 'Ann Cascarano']
date: 1630014805
title: "git branch"
description: "git branch, Main Git command for working with branches."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-branch>.

- List all branches (local and remote; the current branch is highlighted by `*`):

```bash
git branch --all
```

- List which branches include a specific Git commit in their history:

```bash
git branch --all --contains commit_hash
```

- Show the name of the current branch:

```bash
git branch --show-current
```

- Create new branch based on the current commit:

```bash
git branch branch_name
```

- Create new branch based on a specific commit:

```bash
git branch branch_name commit_hash
```

- Rename a branch (must not have it checked out to do this):

```bash
git branch -m old_branch_name new_branch_name
```

- Delete a local branch (must not have it checked out to do this):

```bash
git branch -d branch_name
```

- Delete a remote branch:

```bash
git push remote_name --delete remote_branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-branch: replace --show-current with --contains example (#6387) | 2021-08-26T23:53:25 | [e090e48c45a4](https://github.com/tldr-pages/tldr/commit/e090e48c45a4aa77166ae9dd7b4a160a7b52563b)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Ann Cascarano](mailto:4411121+redrambles@users.noreply.github.com) | git-branch: add command (#3994) | 2020-04-18T19:44:41 | [976cf2ffc8c3](https://github.com/tldr-pages/tldr/commit/976cf2ffc8c3fc835c231754c87db009b29ee661)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-branch: add example to show current branch (#3677) | 2019-12-24T00:09:29 | [9b7cbf8587c7](https://github.com/tldr-pages/tldr/commit/9b7cbf8587c79cc30bba3d3e86db24953122fb33)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[markevan100](mailto:41275604+markevan100@users.noreply.github.com) | git-branch: Add comment that a branch must not be currently checked out in order to delete it (#2651) | 2018-12-16T11:01:47 | [52b6af039e5e](https://github.com/tldr-pages/tldr/commit/52b6af039e5e7725c4fb8bf0dab24b03cd1cc493)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-branch: add example to specify starting point (#2563) | 2018-11-08T10:49:50 | [71af945cf2ff](https://github.com/tldr-pages/tldr/commit/71af945cf2ffab4b96a50d1d3f67259983fb07f0)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-branch.md: various fixes (no content change) - changed token syntax to match project guidelines - added tokens to the rename [...] | 2016-08-24T17:58:53 | [96289e570dd7](https://github.com/tldr-pages/tldr/commit/96289e570dd7af7933825e676bbaed74752ebad5)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | git branch -a lists all branches | 2015-12-28T19:00:06 | [1c82ae15f602](https://github.com/tldr-pages/tldr/commit/1c82ae15f60248fa430b0c64e91b4f7dda52cce2)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Casper Hollingberry](mailto:hollingberry@users.noreply.github.com) | Add missing backtick | 2014-12-21T07:36:16 | [2c6cfbb0e563](https://github.com/tldr-pages/tldr/commit/2c6cfbb0e56344bdf5e060f2780db971259df6ef)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

