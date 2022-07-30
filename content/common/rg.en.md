---
author: ['Feber', 'kalebo', 'Sam Stites', 'Seth Falco', 'Schneider', 'Wyatt Childers', 'Lucas Gabriel Schneider', 'pxgamer', 'Marco Bonelli', 'bl-ue', 'Jacob Wang', 'marchersimon']
date: 1629050349
title: "rg"
description: "rg, Ripgrep is a recursive line-oriented CLI search tool."
categories: "common"
---
> Aims to be a faster alternative to `grep`.

> More information: <https://github.com/BurntSushi/ripgrep>.

- Recursively search the current directory for a regular expression:

```bash
rg regular_expression
```

- Search for regular expressions recursively in the current directory, including hidden files and files listed in `.gitignore`:

```bash
rg --no-ignore --hidden regular_expression
```

- Search for a regular expression only in a certain filetype (e.g. HTML, CSS, etc.):

```bash
rg --type filetype regular_expression
```

- Search for a regular expression only in a subset of directories:

```bash
rg regular_expression set_of_subdirs
```

- Search for a regular expression in files matching a glob (e.g. `README.*`):

```bash
rg regular_expression --glob glob
```

- Only list matched files (useful when piping to other commands):

```bash
rg --files-with-matches regular_expression
```

- Show lines that do not match the given regular expression:

```bash
rg --invert-match regular_expression
```

- Search a literal string pattern:

```bash
rg --fixed-strings -- string
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Wyatt Childers](mailto:DarkArc@users.noreply.github.com) | rg: improved fixed string suggestion (#5995) It's better to include a `--` prior to the search string so that strings starting with [...] | 2021-05-19T17:19:10 | [f2b054d0e1f7](https://github.com/tldr-pages/tldr/commit/f2b054d0e1f746702d79c1d52e97b3f42c1609b8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | rg: update title to match page name; improve examples (#5091) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-06T17:54:01 | [f75ef6661f75](https://github.com/tldr-pages/tldr/commit/f75ef6661f75ec951a082f359d9633821fbf8ba6)
[Jacob Wang](mailto:twang@mdsol.com) | rg: Add doc for literal string search (#3957) | 2020-04-03T03:13:24 | [fbc01dd4630a](https://github.com/tldr-pages/tldr/commit/fbc01dd4630ad327f368c49992eb1bd1b07ef62b)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | rg: fix grammar (#3525) | 2019-11-04T10:54:16 | [5c20a360411d](https://github.com/tldr-pages/tldr/commit/5c20a360411d5b46517368ef710b8908acc1df36)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | ipfs.md: update descrption Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2019-10-13T05:28:04 | [c0fc8b1f2dd0](https://github.com/tldr-pages/tldr/commit/c0fc8b1f2dd00da2a5a5f87b22e2aedb582c34b8)
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: rephrase without adjectives | 2019-10-13T05:28:04 | [42152ed45923](https://github.com/tldr-pages/tldr/commit/42152ed459230c2b244529f0c5990335e0057c6c)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | rg: add link to homepage | 2019-05-29T14:41:10 | [779ca06be2f1](https://github.com/tldr-pages/tldr/commit/779ca06be2f1f64d72bae7f6c9ea900a2aa90c4a)
[Feber](mailto:febrian.setianto@gmail.com) | rg: add -v for invert matching (#2638) | 2018-12-08T13:01:13 | [9cca55203cfe](https://github.com/tldr-pages/tldr/commit/9cca55203cfe67b84c9257a08a0afa76a998c957)
[Sam Stites](mailto:stites@users.noreply.github.com) | rg: Only list matched files (#2302) | 2018-09-06T15:46:53 | [d1377d62c162](https://github.com/tldr-pages/tldr/commit/d1377d62c16214fbaeb00f6d72683ac7dafb283c)
[kalebo](mailto:kaleb.olson@gmail.com) | rg: add page (#1146) | 2016-11-03T04:42:23 | [6d109e5a664a](https://github.com/tldr-pages/tldr/commit/6d109e5a664a88550f5be9234b4a42b120173342)

