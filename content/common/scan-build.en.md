---
author: ['Axel Navarro']
date: 1642512793
title: "scan-build, TLDR Pages"
description: "scan-build, Command-line utility to run a static analyzer over a codebase as part of performing a regular build."
categories: "common"
---
> More information: <https://clang-analyzer.llvm.org/scan-build.html>.

- Build and analyze the project in the current directory:

```bash
scan-build make
```

- Run a command and pass all subsequent options to it:

```bash
scan-build command command_arguments
```

- Display help:

```bash
scan-build
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | scan-build: add page (#7672) | 2022-01-18T14:33:13 | [6a248808bf12](https://github.com/tldr-pages/tldr/commit/6a248808bf12317dfe53036068ce19e0cacc2336)

