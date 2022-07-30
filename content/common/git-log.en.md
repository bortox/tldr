---
author: ['Waldir Pimenta', 'lucas schneider', 'Igor Shubovych', 'kxy', 'Nia Calia-Bogan', 'Larry Lu', 'Todd M. Guerra', 'lord63', 'Daniel Senff', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Ruben Vereecken', 'Jeef', 'thescalaguy', 'Muhammad Falak R Wani']
date: 1635631367
title: "git log"
description: "git log, Show a history of commits."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-log>.

- Show the sequence of commits starting from the current one, in reverse chronological order of the Git repository in the current working directory:

```bash
git log
```

- Show the history of a particular file or directory, including differences:

```bash
git log -p path/to/file_or_directory
```

- Show an overview of which file(s) changed in each commit:

```bash
git log --stat
```

- Show a graph of commits in the current branch using only the first line of each commit message:

```bash
git log --oneline --graph
```

- Show a graph of all commits, tags and branches in the entire repo:

```bash
git log --oneline --decorate --all --graph
```

- Show only commits whose messages include a given string (case-insensitively):

```bash
git log -i --grep search_string
```

- Show the last N commits from a certain author:

```bash
git log -n number --author=author
```

- Show commits between two dates (yyyy-mm-dd):

```bash
git log --before="2017-01-29" --after="2017-01-17"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | git-log: clarify date format with example (#7150) | 2021-10-31T00:02:47 | [11f811cc994d](https://github.com/tldr-pages/tldr/commit/11f811cc994ddea4ff4dd07d254b0da120d2dc18)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Nia Calia-Bogan](mailto:alfriadox@gmail.com) | git-log: update examples (#4293) | 2020-09-11T03:09:44 | [8d745c3a0f31](https://github.com/tldr-pages/tldr/commit/8d745c3a0f31918a8027e6b887038598481a1f1a)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Larry Lu](mailto:pudding850806@gmail.com) | git-log: show branch graph (#2587) | 2018-11-15T11:21:22 | [92ce13cba42f](https://github.com/tldr-pages/tldr/commit/92ce13cba42f99401891f63116702101f51375b1)
[thescalaguy](mailto:fasihxkhatib@gmail.com) | git-log: add --stat example (#2045) | 2018-03-26T17:19:51 | [a3a9afb3b9ea](https://github.com/tldr-pages/tldr/commit/a3a9afb3b9ea1c49584e4bef3d475a10db2b040c)
[Jeef](mailto:jeeftor@users.noreply.github.com) | git-log: add graph view (#1275) | 2017-02-24T08:20:09 | [c63ef4d8d645](https://github.com/tldr-pages/tldr/commit/c63ef4d8d645443bd82379697c65bb1ba0edc0e5)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-log.md: improve descriptions, add --grep (#1012) | 2016-10-25T19:22:47 | [669e845d3fa7](https://github.com/tldr-pages/tldr/commit/669e845d3fa79c6a8844cee9013cfe5c666d3232)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Merge pull request #304 from gutsy/master Add some extra detail to git log command | 2015-12-06T22:36:43 | [ade3c5c4e761](https://github.com/tldr-pages/tldr/commit/ade3c5c4e7615038eb04bd626f8134f5cc4e82c3)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Todd M. Guerra](mailto:toddguerra@gmail.com) | Remove q info and change path to correct format Removed q as it’s kind of generic and applies to many commands. Also changed PATH to [...] | 2015-10-12T16:23:23 | [5dea29f48cfa](https://github.com/tldr-pages/tldr/commit/5dea29f48cfa0b2d82daf74b82842f7bfbe2d424)
[Todd M. Guerra](mailto:toddguerra@gmail.com) | Add some extra detail to git log command Added the useful —oneline flag and also info on how to quit out (since I always forget). | 2015-10-09T22:00:28 | [85262973facd](https://github.com/tldr-pages/tldr/commit/85262973facd0f88efb125e4471e1ce256146db6)
[Daniel Senff](mailto:mail@danielsenff.de) | Update git-log.md adds the command for displaying a detailed git history of a particular file or folder | 2014-03-31T14:08:45 | [498827675936](https://github.com/tldr-pages/tldr/commit/498827675936a41127a6e2a0394405c6a2f5518e)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

