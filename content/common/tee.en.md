---
author: ['Dario Vladović', 'Agniva De Sarker', 'Like-all', 'Polle Vanhoof', 'Jessica Stokes', 'lord63', 'Marco Bonelli', 'Ruben Vereecken', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "tee"
description: "tee, Read from standard input and write to standard output and files (or commands)."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/tee>.

- Copy standard input to each file, and also to standard output:

```bash
echo "example" | tee path/to/file
```

- Append to the given files, do not overwrite:

```bash
echo "example" | tee -a path/to/file
```

- Print standard input to the terminal, and also pipe it into another program for further processing:

```bash
echo "example" | tee /dev/tty | xargs printf "[%s]"
```

- Create a directory called "example", count the number of characters in "example" and write "example" to the terminal:

```bash
echo "example" | tee >(xargs mkdir) >(wc -c)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tee: add more information link (#5629) | 2021-03-30T15:33:07 | [002c666040f3](https://github.com/tldr-pages/tldr/commit/002c666040f36651b08e509262e0e22f7a03bf7a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Jessica Stokes](mailto:hello@jessicastokes.net) | tee: add `tee /dev/tty` mid-pipeline example (#2343) | 2018-09-21T21:15:43 | [eb00419cdcc4](https://github.com/tldr-pages/tldr/commit/eb00419cdcc41047d2941addc53cce54c5d375f0)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | tee.md: added missing quotes | 2017-10-28T13:19:38 | [f3e1e62cdf95](https://github.com/tldr-pages/tldr/commit/f3e1e62cdf955a150bb0b04512647986accb6fad)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | tee: add missing backtick | 2017-10-28T12:40:48 | [71ad96a7e511](https://github.com/tldr-pages/tldr/commit/71ad96a7e5116b6c44696df72c20469b59fafe62)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | tee: proposed change for review | 2017-10-28T12:20:16 | [877e017f00eb](https://github.com/tldr-pages/tldr/commit/877e017f00ebbac1acac21e9cf9f21f43106cdd3)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | tee: final cleanup formatting | 2017-10-27T12:23:17 | [d8fc8ce6f1dc](https://github.com/tldr-pages/tldr/commit/d8fc8ce6f1dc8d8fa564471910a9f40107b36472)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | tee: update language as per remarks | 2017-10-26T19:50:49 | [6cc2bfaccb0f](https://github.com/tldr-pages/tldr/commit/6cc2bfaccb0f7741c9aae7d0d4c45e41cdcd2a08)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | tee: Add usecase for process substitution | 2017-10-26T16:25:39 | [90f25a7e6283](https://github.com/tldr-pages/tldr/commit/90f25a7e6283b44e5537afa46774c9dc4daf8e45)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Like-all](mailto:like-all@yandex.com) | common: tee | 2014-09-11T16:37:41 | [67e91a371767](https://github.com/tldr-pages/tldr/commit/67e91a371767e30cd3990ada6f21b6be61500e62)

