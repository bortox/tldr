---
author: ['pixel']
date: 1631349152
title: "clang++, TLDR Pages"
description: "clang++, Compiles C++ source files."
categories: "common"
---
> Part of LLVM.

> More information: <https://clang.llvm.org>.

- Compile a source code file into an executable binary:

```bash
clang++ path/to/source.cpp -o path/to/output_executable
```

- Display (almost) all errors and warnings:

```bash
clang++ path/to/source.cpp -Wall -o path/to/output_executable
```

- Choose a language standard to compile with:

```bash
clang++ path/to/source.cpp -std=c++20 -o path/to/output_executable
```

- Include libraries located at a different path than the source file:

```bash
clang++ path/to/source.cpp -o path/to/output_executable -Ipath/to/header_path -Lpath/to/library_path -lpath/to/library_name
```

- Compile source code into LLVM Intermediate Representation (IR):

```bash
clang++ -S -emit-llvm path/to/source.cpp -o path/to/output.ll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | clang++: add page (#6501) | 2021-09-11T10:32:32 | [d729cff839fd](https://github.com/tldr-pages/tldr/commit/d729cff839fda58eb9ebb7380392b4ad5643fcc9)

