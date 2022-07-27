---
author: ['lbonn', 'pxgamer']
date: 1560099229
title: "ctest, TLDR Pages"
description: "ctest, CMake test driver program."
categories: "common"
---
> More information: <https://gitlab.kitware.com/cmake/community/wikis/doc/ctest/Testing-With-CTest>.

- Run all tests defined in the CMake project, executing 4 jobs at a time in parallel:

```bash
ctest -j4 --output-on-failure
```

- Show a list of available tests:

```bash
ctest -N
```

- Run a single test based on its name, or filter on a regular expression:

```bash
ctest --output-on-failure -R '^test_name$'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | ctest: add link to homepage | 2019-06-09T18:53:49 | [958fe9751f62](https://github.com/tldr-pages/tldr/commit/958fe9751f62c8d81ac52e548972d1249a1c20c7)
[lbonn](mailto:lbonn@users.noreply.github.com) | ctest: add page (#2590) | 2018-11-21T18:06:48 | [0372f087b850](https://github.com/tldr-pages/tldr/commit/0372f087b85065d37a1890b8fa94d280f97928c3)

