---
author: ['Benedek Szilvasy']
date: 1635474888
title: "lli, TLDR Pages"
description: "lli, Directly execute programs from LLVM bitcode."
categories: "common"
---
> More information: <https://www.llvm.org/docs/CommandGuide/lli.html>.

- Execute a bitcode or IR file:

```bash
lli path/to/file.ll
```

- Execute with command line arguments:

```bash
lli path/to/file.ll argument1 argument2 ...
```

- Enable all optimizations:

```bash
lli -O3 path/to/file.ll
```

- Load a dynamic library before linking:

```bash
lli --dlopen=path/to/library.dll path/to/file.ll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Benedek Szilvasy](mailto:benedek.szilvasy@gmail.com) | lli: add page (#7256) | 2021-10-29T04:34:48 | [a014befa5aac](https://github.com/tldr-pages/tldr/commit/a014befa5aac83e1941619c0401217032a5b396d)

