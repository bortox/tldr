---
author: ['sebastientinel', 'Peter Tripp', 'rprieto', 'Srinivasan R', 'Marco Bonelli', 'Ruben Vereecken']
date: 1603905583
title: "srm"
description: "srm, Securely remove files or directories."
categories: "common"
---
> Overwrites the existing data one or multiple times. Drop in replacement for rm.

> More information: <http://srm.sourceforge.net/srm.html>.

- Remove a file after a single-pass overwriting with random data:

```bash
srm -s path/to/file
```

- Remove a file after seven passes of overwriting with random data:

```bash
srm -m path/to/file
```

- Recursively remove a directory and its contents overwriting each file with a single-pass of random data:

```bash
srm -r -s path/to/directory
```

- Prompt before every removal:

```bash
srm -i \*
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Peter Tripp](mailto:petertripp@gmail.com) | Single line text refinements. | 2016-01-20T19:04:06 | [750580dbe6da](https://github.com/tldr-pages/tldr/commit/750580dbe6dacb98141b4dc805535a9e043ceedb)
[Peter Tripp](mailto:petertripp@gmail.com) | Linting fixes. | 2016-01-20T12:52:51 | [f36e1216811a](https://github.com/tldr-pages/tldr/commit/f36e1216811ad449019c9fd2bc361cb2a0208894)
[Peter Tripp](mailto:petertripp@gmail.com) | srm: Condense and reword. Remove 35-pass example cause it's crazy-town. | 2016-01-20T12:42:47 | [a53e772333b5](https://github.com/tldr-pages/tldr/commit/a53e772333b5f6829f8fe85e70a260be75fbfe28)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Add extra newline between consecutive commands examples. These 6 files had multiple examples all separated by a single newline. While [...] | 2015-10-28T18:10:44 | [2097cf359d9b](https://github.com/tldr-pages/tldr/commit/2097cf359d9bc97448a1dceb5b9549426159ea69)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

