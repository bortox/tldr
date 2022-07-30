---
author: ['Lucas Gabriel Schneider', 'Markus Pielmeier']
date: 1612112718
title: "clang-format"
description: "clang-format, Tool to auto-format C/C++/Java/JavaScript/Objective-C/Protobuf/C# code."
categories: "common"
---
> More information: <https://clang.llvm.org/docs/ClangFormat.html>.

- Format a file and print the result to stdout:

```bash
clang-format path/to/file
```

- Format a file in-place:

```bash
clang-format -i path/to/file
```

- Format a file using a predefined coding style:

```bash
clang-format --style=LLVM|Google|Chromium|Mozilla|WebKit path/to/file
```

- Format a file using the `.clang-format` file in one of the parent directories of the source file:

```bash
clang-format --style=file path/to/file
```

- Generate a custom `.clang-format` file:

```bash
clang-format --style=LLVM|Google|Chromium|Mozilla|WebKit --dump-config > .clang-format
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Markus Pielmeier](mailto:markuspi@users.noreply.github.com) | clang-format: add page (#4736) | 2020-10-24T14:40:29 | [b8a1ccc2005c](https://github.com/tldr-pages/tldr/commit/b8a1ccc2005cae5b16f4c757f36f753c8df28f36)

