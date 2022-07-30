---
author: ['pixel']
date: 1631611739
title: "llvm-config"
description: "llvm-config, Get various configuration information needed to compile programs which use LLVM."
categories: "common"
---
> Typically called from build systems, like in Makefiles or configure scripts.

> More information: <https://llvm.org/docs/CommandGuide/llvm-config.html>.

- Compile and link an LLVM based program:

```bash
clang++ $(llvm-config --cxxflags --ldflags --libs) --output path/to/output_executable path/to/source.cc
```

- Print the `PREFIX` of your LLVM installation:

```bash
llvm-config --prefix
```

- Print all targets supported by your LLVM build:

```bash
llvm-config --targets-built
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | llvm-config: add page (#6498) | 2021-09-14T11:28:59 | [ac306cf14845](https://github.com/tldr-pages/tldr/commit/ac306cf148458d1fe9581331c8c0fd26229ed64e)

