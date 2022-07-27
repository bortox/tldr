---
author: ['Waldir Pimenta', 'lord63', 'Seth Woodworth', 'Marco Bonelli', 'Ruben Vereecken', 'fejx', 'Mehdi FARSI', 'kxy', 'lmazardo', 'Mike Rogne', 'Starbeamrainbowlabs', 'Te-Chi Liu']
date: 1590150684
title: "git checkout, TLDR Pages"
description: "git checkout, Checkout a branch or paths to the working tree."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-checkout>.

- Create and switch to a new branch:

```bash
git checkout -b branch_name
```

- Create and switch to a new branch based on a specific reference (branch, remote/branch, tag are examples of valid references):

```bash
git checkout -b branch_name reference
```

- Switch to an existing local branch:

```bash
git checkout branch_name
```

- Switch to the previously checked out branch:

```bash
git checkout -
```

- Switch to an existing remote branch:

```bash
git checkout --track remote_name/branch_name
```

- Discard all unstaged changes in the current directory (see `git reset` for more undo-like commands):

```bash
git checkout .
```

- Discard unstaged changes to a given file:

```bash
git checkout filename
```

- Replace a file in the current directory with the version of it committed in a given branch:

```bash
git checkout branch_name -- filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[fejx](mailto:florian.jhn@gmail.com) | Change all occurrences of file_name to filename (#4059) | 2020-05-22T14:31:24 | [4e1662b729ba](https://github.com/tldr-pages/tldr/commit/4e1662b729ba2bc23f7c12f606d41a86a613f8ea)
[lmazardo](mailto:luc@mazardo.com) | git-checkout: add example to go to previous branch (#3319) | 2019-10-06T09:21:23 | [97bc3a92f97f](https://github.com/tldr-pages/tldr/commit/97bc3a92f97fd2d1619be9d4080376cb242e4388)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Mike Rogne](mailto:mike@infinitywebcreations.com) | git checkout: add example for creating new branch based on remote branch with different name (#2494) | 2018-10-28T01:52:23 | [3bf256f6cbf5](https://github.com/tldr-pages/tldr/commit/3bf256f6cbf547832c5d938d62a962c80ea865ed)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-checkout: "modifications" --> "changes" | 2017-05-18T18:24:52 | [05780d6183e8](https://github.com/tldr-pages/tldr/commit/05780d6183e838c11e881d1a3cdb7c778d99d211)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-checkout: mention reset, add single-file ex. | 2017-05-18T18:24:52 | [6f9dbe9fce90](https://github.com/tldr-pages/tldr/commit/6f9dbe9fce90b6f8efd0d6049b88a6afad1c19bc)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-checkout: correct checkout of remote branch (#1359) As described in http://stackoverflow.com/a/9537923 (paraphrased below): > You [...] | 2017-04-30T12:17:03 | [2a4379ceea9f](https://github.com/tldr-pages/tldr/commit/2a4379ceea9fa2626b6b4242ea03e36190d3861d)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-checkout: also works for remote branches (#1238) | 2017-01-18T15:43:53 | [b7d34523f657](https://github.com/tldr-pages/tldr/commit/b7d34523f657e56cbf28695a7dec0c7d07ad36fb)
[Seth Woodworth](mailto:seth@sethish.com) | Add git-checkout example for files across branches | 2017-01-06T05:43:46 | [e04863b55d3e](https://github.com/tldr-pages/tldr/commit/e04863b55d3e59825c2384f0fba8a46ace4eaf30)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed annoyingly incorrect file syntaxes | 2016-01-07T16:51:03 | [b755e726c8b4](https://github.com/tldr-pages/tldr/commit/b755e726c8b452066bf3bc3b5334f462eac37d20)
[Mehdi FARSI](mailto:mehdifarsi.pro@gmail.com) | Undo unstaged local modification | 2015-11-24T00:21:20 | [0d2cfc2e3d47](https://github.com/tldr-pages/tldr/commit/0d2cfc2e3d47dc2713339f54df9d59ec56836a67)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

