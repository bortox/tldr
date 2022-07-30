---
author: ['Eiman', 'Agniva De Sarker', 'fejx', 'e0i', 'Like-all', 'Axel Navarro', 'lord63', 'abe', 'Ruben Vereecken', 'Seth Woodworth', 'marchersimon']
date: 1641649180
title: "dpkg"
description: "dpkg, Debian package manager."
categories: "linux"
---
> Some subcommands such as `dpkg deb` have their own usage documentation.

> More information: <https://manpages.debian.org/latest/dpkg/dpkg.html>.

- Install a package:

```bash
dpkg -i path/to/file.deb
```

- Remove a package:

```bash
dpkg -r package_name
```

- List installed packages:

```bash
dpkg -l pattern
```

- List a package's contents:

```bash
dpkg -L package_name
```

- List contents of a local package file:

```bash
dpkg -c path/to/file.deb
```

- Find out which package owns a file:

```bash
dpkg -S filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Eiman](mailto:eimanip@users.noreply.github.com) | dpkg: add more information link (#4673) | 2020-10-13T12:49:56 | [c6fb2a45b343](https://github.com/tldr-pages/tldr/commit/c6fb2a45b343d671686d296738634fa29bfe6e14)
[fejx](mailto:florian.jhn@gmail.com) | Change all occurrences of file_name to filename (#4059) | 2020-05-22T14:31:24 | [4e1662b729ba](https://github.com/tldr-pages/tldr/commit/4e1662b729ba2bc23f7c12f606d41a86a613f8ea)
[abe](mailto:muendelezaji@gmail.com) | dpkg: add -c option (list local deb file contents) Add example for listing package contents of a downloaded `.deb` file, because `dpkg [...] | 2018-09-03T18:30:46 | [d76966122768](https://github.com/tldr-pages/tldr/commit/d7696612276835826210b051b6993ff022c6a75c)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | dpkg: Fix travis errors (#1223) | 2017-01-02T18:36:30 | [7ba512e303f4](https://github.com/tldr-pages/tldr/commit/7ba512e303f4292865e9cbf5fa61bd8b1b39d89b)
[Seth Woodworth](mailto:seth@sethish.com) | Adds dpkg note for finding which package owns a file | 2017-01-02T17:54:34 | [6d3294dcbef1](https://github.com/tldr-pages/tldr/commit/6d3294dcbef13203018e6f0014766f6b7e47770a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[e0i](mailto:e0i@users.noreply.github.com) | Fixed a typo in dpkg | 2015-09-23T12:17:08 | [3d37dfc84cad](https://github.com/tldr-pages/tldr/commit/3d37dfc84cad38a798b210e4cb9e637c0dc7ba29)
[Like-all](mailto:lik3a11@gmail.com) | Pages: dpkg | 2014-04-28T23:19:22 | [4a50dd2484f7](https://github.com/tldr-pages/tldr/commit/4a50dd2484f7a9426f31d9b101a486b226c89f2f)

