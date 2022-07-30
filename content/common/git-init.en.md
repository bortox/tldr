---
author: ['lucas schneider', 'Axel Navarro', 'lord63', 'Starbeamrainbowlabs', 'Marco Bonelli', 'kxy', 'Seth Woodworth', 'Ruben Vereecken']
date: 1621437616
title: "git init"
description: "git init, Initializes a new local Git repository."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-init>.

- Initialize a new local repository:

```bash
git init
```

- Initialize a repository with the specified name for the initial branch:

```bash
git init --initial-branch=branch_name
```

- Initialize a repository using SHA256 for object hashes (requires Git version 2.29+):

```bash
git init --object-format=sha256
```

- Initialize a barebones repository, suitable for use as a remote over ssh:

```bash
git init --bare
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-init: add --initial-branch example (#5990) | 2021-05-19T17:20:16 | [9c2d5b51a618](https://github.com/tldr-pages/tldr/commit/9c2d5b51a618edd413a19585ec725e294e65b0e4)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-init: add --object-format example (#4888) | 2020-10-30T13:28:18 | [04591b14dc71](https://github.com/tldr-pages/tldr/commit/04591b14dc715036f6cb31f71350a60efff212ad)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted git pages | 2016-01-21T13:08:45 | [d72dea793175](https://github.com/tldr-pages/tldr/commit/d72dea793175ac3b51c4e5c482403fddf8011737)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Merge branch 'master' of git://github.com/sethwoodworth/tldr into sethwoodworth-master Conflicts: pages/common/git-init.md | 2016-01-21T13:08:07 | [d00c14960da4](https://github.com/tldr-pages/tldr/commit/d00c14960da481bd65b3a567786b40a3c3211b1d)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Seth Woodworth](mailto:seth.ww@thelevelup.com) | Expands description of --bare git-init option | 2015-12-30T19:54:58 | [a0f62e582a44](https://github.com/tldr-pages/tldr/commit/a0f62e582a445ccfc46b8e0bbdd3c6097560b78b)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

