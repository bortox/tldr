---
author: ['Irina', 'Dario Vladović', 'Igor Shubovych', 'André König', 'Henrikh Kantuni', 'Peter Tripp', 'blalyasar', 'rprieto', 'Axel Navarro', 'Srinivasan R', 'Haruki', 'Sarada Lee', 'Caleb Browne', 'Ruben Vereecken', 'Seth Falco', 'marchersimon']
date: 1634106377
title: "ls"
description: "ls, List directory contents."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/ls>.

- List files one per line:

```bash
ls -1
```

- List all files, including hidden files:

```bash
ls -a
```

- List all files, with trailing `/` added to directory names:

```bash
ls -F
```

- Long format list (permissions, ownership, size, and modification date) of all files:

```bash
ls -la
```

- Long format list with size displayed using human-readable units (KiB, MiB, GiB):

```bash
ls -lh
```

- Long format list sorted by size (descending):

```bash
ls -lS
```

- Long format list of all files, sorted by modification date (oldest first):

```bash
ls -ltr
```

- Only list directories:

```bash
ls -d */
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | *: refresh Russian translation (#6850) | 2021-10-13T08:26:17 | [639b2e4e10c7](https://github.com/tldr-pages/tldr/commit/639b2e4e10c73c8014036c302192e4faa51e5279)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[blalyasar](mailto:49458946+blalyasar@users.noreply.github.com) | ls, touch: add examples (#5855) | 2021-05-14T02:40:50 | [40e478add979](https://github.com/tldr-pages/tldr/commit/40e478add979658bc5956988739dc62218235f3f)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[Henrikh Kantuni](mailto:henrikh.kantuni@gmail.com) | ls: fix typo (#5228) | 2021-02-03T18:37:37 | [c61c31dc3a65](https://github.com/tldr-pages/tldr/commit/c61c31dc3a6519a7f166c7c5e1777309528e0c90)
[Sarada Lee](mailto:28886668+slee5777@users.noreply.github.com) | Update ls.md by adding ls -F (#4071) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-05-27T16:17:56 | [4278e7b93586](https://github.com/tldr-pages/tldr/commit/4278e7b93586f1c3555647e7210cb1b5e647747f)
[Caleb Browne](mailto:CBrowne@users.noreply.github.com) | Update ls.md | 2016-01-27T17:44:05 | [2cdad11a3113](https://github.com/tldr-pages/tldr/commit/2cdad11a31137dbd0f14cfdadb0536df5839c675)
[Caleb Browne](mailto:CBrowne@users.noreply.github.com) | Adding long format list sorted by reverse mod date | 2016-01-27T17:31:40 | [92611c992ba6](https://github.com/tldr-pages/tldr/commit/92611c992ba6b09496509189ace2f5948b6684d5)
[Peter Tripp](mailto:petertripp@gmail.com) | Single line text refinements. | 2016-01-20T19:04:06 | [750580dbe6da](https://github.com/tldr-pages/tldr/commit/750580dbe6dacb98141b4dc805535a9e043ceedb)
[Peter Tripp](mailto:petertripp@gmail.com) | LS: Condense examples to single line, removing glob and sorting examples. | 2016-01-20T12:39:15 | [c0dad323d9db](https://github.com/tldr-pages/tldr/commit/c0dad323d9db0e847a68763656b0f2d4703e10e9)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Remove -s from ls -ls | 2015-12-16T12:35:07 | [fabd1f8c9edc](https://github.com/tldr-pages/tldr/commit/fabd1f8c9edcb9a1f9ef3445644ff2b55aa4a194)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Add extra newline between consecutive commands examples. These 6 files had multiple examples all separated by a single newline. While [...] | 2015-10-28T18:10:44 | [2097cf359d9b](https://github.com/tldr-pages/tldr/commit/2097cf359d9bc97448a1dceb5b9549426159ea69)
[Haruki](mailto:haruki.takechi@mi9.com.au) | Fix the ls command sorting options | 2014-09-17T18:13:24 | [f7b5a9c5b467](https://github.com/tldr-pages/tldr/commit/f7b5a9c5b467cd321e4af7c31c1cda2ffc90d640)
[André König](mailto:andre.koenig@gmail.com) | Added example which displays the size in a human readable format. | 2014-04-16T20:24:01 | [f62e295682f7](https://github.com/tldr-pages/tldr/commit/f62e295682f7c8978dba6bbfef4349640e560802)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

