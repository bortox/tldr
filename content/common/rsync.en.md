---
author: ['quarcu', 'Melwin Kieffer', 'Jake Vossen', 'Piotr Szwarc', 'Kang Jinwon', 'Ondrej Brinkel', 'Ruben Vereecken', 'Matthew', 'Dylan Khor', 'Laura Dietz', 'lord63', 'Nick Smyrnioudis', 'Sadeed', 'rprieto', 'Waldir Pimenta', 'Shadab Zafar', 'Marco Bonelli', 'Ryan Nevius', 'Corey Harris', 'Giovanni Geraci']
date: 1645389844
title: "rsync, TLDR Pages"
description: "rsync, Transfer files either to or from a remote host (not between two remote hosts)."
categories: "common"
---
> Can transfer single files, or multiple files matching a pattern.

> More information: <https://manned.org/rsync>.

- Transfer file from local to remote host:

```bash
rsync path/to/local_file remote_host:path/to/remote_directory
```

- Transfer file from remote host to local:

```bash
rsync remote_host:path/to/remote_file path/to/local_directory
```

- Transfer file in [a]rchive (to preserve attributes) and compressed ([z]ipped) mode with [v]erbose and [h]uman-readable [P]rogress:

```bash
rsync -azvhP path/to/local_file remote_host:path/to/remote_directory
```

- Transfer a directory and all its children from a remote to local:

```bash
rsync -r remote_host:path/to/remote_directory path/to/local_directory
```

- Transfer directory contents (but not the directory itself) from a remote to local:

```bash
rsync -r remote_host:path/to/remote_directory/ path/to/local_directory
```

- Transfer a directory [r]ecursively, in [a]rchive to preserve attributes, resolving contained soft[l]inks , and ignoring already transferred files [u]nless newer:

```bash
rsync -rauL remote_host:path/to/remote_directory path/to/local_directory
```

- Transfer file over SSH and delete remote files that do not exist locally:

```bash
rsync -e ssh --delete remote_host:path/to/remote_file path/to/local_file
```

- Transfer file over SSH using a different port than the default and show global progress:

```bash
rsync -e 'ssh -p port' --info=progress2 remote_host:path/to/remote_file path/to/local_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jake Vossen](mailto:jake@vossen.dev) | rsync: fix remote_directory in -rauL example (#7795) | 2022-02-20T21:44:04 | [1b9e38cb1bc6](https://github.com/tldr-pages/tldr/commit/1b9e38cb1bc6aba7c6ac315759483e138bb749c8)
[Shadab Zafar](mailto:dufferzafar0@gmail.com) | rsync: fix --delete doc (#7379) | 2021-11-07T13:27:01 | [2860c8019645](https://github.com/tldr-pages/tldr/commit/2860c801964518c8a2b606445349ca6910c66562)
[Sadeed](mailto:sadeeedw@gmail.com) | rar, read, renice, rev, roll, route, rsync: add link (#6929) | 2021-10-13T08:22:50 | [6583ef2421da](https://github.com/tldr-pages/tldr/commit/6583ef2421da704fdb94b1acb67c70936ccb5ddf)
[Giovanni Geraci](mailto:geraci.giovanni@gmail.com) | rsync: fix example description (#4866) | 2020-10-26T12:52:26 | [0162480727a3](https://github.com/tldr-pages/tldr/commit/0162480727a38d551ee2b1474d8f2c048028f2bb)
[Nick Smyrnioudis](mailto:32795986+NickSmyr@users.noreply.github.com) | rsync: edit example for use a different port for ssh (#4359) | 2020-10-17T22:27:38 | [fe00e563984a](https://github.com/tldr-pages/tldr/commit/fe00e563984abd16a839cd986c0b3b1c0d1e00c8)
[Laura Dietz](mailto:dietz@cs.unh.edu) | rsync: add -rauL option (#3802) Co-authored-by: Agniva De Sarker <agnivade@yahoo.co.in> | 2020-02-06T16:11:32 | [206e00387d23](https://github.com/tldr-pages/tldr/commit/206e00387d2382e1e2a93bebce2bd09cddae9cf5)
[Ryan Nevius](mailto:ryanevius@gmail.com) | rsync: Match path style for other popular commands e.g. use `path/to/local_file` instead of `local_file` | 2019-05-24T10:03:17 | [e9ad70e30cec](https://github.com/tldr-pages/tldr/commit/e9ad70e30cec94494a863bb2e2aca77da819eefd)
[Ryan Nevius](mailto:ryanevius@gmail.com) | rsync: standardize verbiage Use "directory" instead of "folder" | 2019-05-24T10:03:17 | [6f876373a185](https://github.com/tldr-pages/tldr/commit/6f876373a185335973970d2cd58f907b4fb343e7)
[Corey Harris](mailto:daswerth@gmail.com) | rsync: add -r example with trailing backslash (#2760) | 2019-02-11T14:49:40 | [94230238de48](https://github.com/tldr-pages/tldr/commit/94230238de48343455360062c958573ecc8e65cd)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Melwin Kieffer](mailto:melwinkieffer@gmail.com) | rsync: add --delete example (#2595) Replace --progress by --delete because it is already shown in 3rd example with options -P | 2018-11-15T14:29:11 | [ebb543966627](https://github.com/tldr-pages/tldr/commit/ebb5439666278b3aa8af7c09333a510b8c1d63b6)
[Dylan Khor](mailto:thekhord@gmail.com) | rsync: modify one example with more useful flags (#2477) | 2018-10-24T20:58:54 | [25441c625106](https://github.com/tldr-pages/tldr/commit/25441c625106bbd0a900d9f03bacb035473ac362)
[Ondrej Brinkel](mailto:der-On@users.noreply.github.com) | rsync: removed trailing white space | 2017-12-05T19:45:51 | [915bec1e0031](https://github.com/tldr-pages/tldr/commit/915bec1e0031f661a151ecefe0855638135e4b0c)
[Ondrej Brinkel](mailto:der-On@users.noreply.github.com) | added rsync global progress | 2017-12-05T19:37:48 | [6b953f6a20cf](https://github.com/tldr-pages/tldr/commit/6b953f6a20cf1792fac0a54921ed9fee7e052d34)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix descriptions split by mistake in #633 (#1098) | 2016-10-12T17:58:04 | [c15d705d4007](https://github.com/tldr-pages/tldr/commit/c15d705d4007cc9adfa737a0ec6b88bef56656a8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Merge branch 'master' of git://github.com/matthewgao/tldr into matthewgao-master Conflicts: pages/common/rsync.md | 2016-01-18T11:36:14 | [5f1ce2c2d263](https://github.com/tldr-pages/tldr/commit/5f1ce2c2d2631b3112e3832ece6184fb0c430458)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Kang Jinwon](mailto:kjwonmail@gmail.com) | Update rsync.md | 2015-12-29T17:40:29 | [3b6153bf96b4](https://github.com/tldr-pages/tldr/commit/3b6153bf96b4bf0eaa9e1385d6257a1cb8c2e252)
[Matthew](mailto:matthewgao@gmail.com) | better than better better than better | 2015-12-29T06:03:08 | [d693904250ae](https://github.com/tldr-pages/tldr/commit/d693904250aeb8a22e91631f20703deca5efe47d)
[Matthew](mailto:matthewgao@gmail.com) | Update description Update description | 2015-12-29T05:44:42 | [86321bcb0e5a](https://github.com/tldr-pages/tldr/commit/86321bcb0e5af9e5f48a4dc3477281b091c229d0)
[Matthew](mailto:matthewgao@gmail.com) | reduce the explanation. reduce the explanation. | 2015-12-28T13:06:22 | [67e4f1351614](https://github.com/tldr-pages/tldr/commit/67e4f1351614e278a84ebf0b5ddd03bc3cb3291c)
[Matthew](mailto:matthewgao@gmail.com) | remove duplicate line and add a new common usage. remove duplicate lines and add a new common usage of '-avz' | 2015-12-28T06:05:55 | [5b80fe345f8a](https://github.com/tldr-pages/tldr/commit/5b80fe345f8af8a018e29bd4754e35d682cf809c)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Piotr Szwarc](mailto:quarcu@users.noreply.github.com) | Update rsync.md Reduced flags for rsync over ssh. | 2015-03-12T10:23:56 | [bacc874cab3a](https://github.com/tldr-pages/tldr/commit/bacc874cab3a6a897d5c3a3863e720b706f839db)
[quarcu](mailto:quarcu@users.noreply.github.com) | Update rsync.md Added rsync over SSH | 2015-02-28T19:09:18 | [65abc7f38d63](https://github.com/tldr-pages/tldr/commit/65abc7f38d63b66305e3725b2597d6fc20c1fe23)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

