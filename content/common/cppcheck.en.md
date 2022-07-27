---
author: ['Marco Bonelli', 'Guido Lena Cota', 'pxgamer', 'Waldir Pimenta']
date: 1560099229
title: "cppcheck, TLDR Pages"
description: "cppcheck, A static analysis tool for C/C++ code."
categories: "common"
---
> Instead of syntax errors, it focuses on the types of bugs that compilers normally do not detect.

> More information: <http://cppcheck.sourceforge.net>.

- Recursively check the current directory, showing progress on the screen and logging error messages to a file:

```bash
cppcheck . 2> cppcheck.log
```

- Recursively check a given directory, and don't print progress messages:

```bash
cppcheck --quiet path/to/directory
```

- Check a given file, specifying which tests to perform (by default only errors are shown):

```bash
cppcheck --enable=error|warning|style|performance|portability|information|all path/to/file.cpp
```

- List available tests:

```bash
cppcheck --errorlist
```

- Check a given file, ignoring specific tests:

```bash
cppcheck --suppress=test_id1 --suppress=test_id2 path/to/file.cpp
```

- Check the current directory, providing paths for include files located outside it (e.g. external libraries):

```bash
cppcheck -I include/directory_1 -I include/directory_2 .
```

- Check a Microsoft Visual Studio project (`*.vcxproj`) or solution (`*.sln`):

```bash
cppcheck --project=path/to/project.sln
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | cppcheck: add link to homepage | 2019-06-09T18:53:49 | [8a28043e3fbd](https://github.com/tldr-pages/tldr/commit/8a28043e3fbdc9de19de079d561c397a8ac659a1)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | cppcheck: simplify example (#2937) | 2019-04-22T14:44:54 | [07fe98693de6](https://github.com/tldr-pages/tldr/commit/07fe98693de6fa54d1c2f1d7ec227f01d2027a00)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cppcheck: add page (#1212) | 2016-12-28T16:26:07 | [1617567b827a](https://github.com/tldr-pages/tldr/commit/1617567b827a345f7a2142a9b1ce5a65f632825a)

