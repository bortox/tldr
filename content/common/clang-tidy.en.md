---
author: ['Jan Hensel']
date: 1635796855
title: "clang-tidy, TLDR Pages"
description: "clang-tidy, An LLVM-based C/C++ linter to find style violations, bugs and security flaws through static analysis."
categories: "common"
---
> More information: <https://clang.llvm.org/extra/clang-tidy/>.

- Run default checks on a source file:

```bash
clang-tidy path/to/file.cpp
```

- Don't run any checks other than the `cppcoreguidelines` checks on a file:

```bash
clang-tidy path/to/file.cpp -checks=-*,cppcoreguidelines-*
```

- List all available checks:

```bash
clang-tidy -checks=* -list-checks
```

- Specify defines and includes as compilation options (after `--`):

```bash
clang-tidy path/to/file.cpp -- -Imy_project/include -Ddefinitions
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jan Hensel](mailto:63857598+ja-he@users.noreply.github.com) | clang-tidy: add page (#7232) | 2021-11-01T21:00:55 | [678d79f57788](https://github.com/tldr-pages/tldr/commit/678d79f57788d300ffe212c23af754bbd799fd5e)

