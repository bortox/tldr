---
author: ['ev-john', 'Lucas Gabriel Schneider']
date: 1612112718
title: "gcov, TLDR Pages"
description: "gcov, Code coverage analysis and profiling tool that discovers untested parts of a program."
categories: "linux"
---
> Also displays a copy of source code annotated with execution frequencies of code segments.

> More information: <https://gcc.gnu.org/onlinedocs/gcc/Invoking-Gcov.html>.

- Generate a coverage report named `file.cpp.gcov`:

```bash
gcov path/to/file.cpp
```

- Write individual execution counts for every basic block:

```bash
gcov --all-blocks path/to/file.cpp
```

- Write branch frequencies to the output file and print summary information to stdout as a percentage:

```bash
gcov --branch-probabilities path/to/file.cpp
```

- Write branch frequencies as the number of branches taken, rather than the percentage:

```bash
gcov --branch-counts path/to/file.cpp
```

- Do not create a `gcov` output file:

```bash
gcov --no-output path/to/file.cpp
```

- Write file level as well as function level summaries:

```bash
gcov --function-summaries path/to/file.cpp
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[ev-john](mailto:56849582+ev-john@users.noreply.github.com) | gcov: add page (#4723) | 2020-10-24T14:13:51 | [90a3a2e1c767](https://github.com/tldr-pages/tldr/commit/90a3a2e1c767428f172951adabc741cb9d36b6e5)

