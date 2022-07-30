---
author: ['pixel']
date: 1630584933
title: "adscript"
description: "adscript, Compiler for Adscript files."
categories: "common"
---
> More information: <https://github.com/Amplus2/Adscript>.

- Compile a file to an object file:

```bash
adscript --output path/to/file.o path/to/input_file.adscript
```

- Compile and link a file to a standalone executable:

```bash
adscript --executable --output path/to/file path/to/input_file.adscript
```

- Compile a file to LLVM IR instead of native machine code:

```bash
adscript --llvm-ir --output path/to/file.ll path/to/input_file.adscript
```

- Cross-compile a file to an object file for a foreign CPU architecture or operating system:

```bash
adscript --target-triple i386-linux-elf --output path/to/file.o path/to/input_file.adscript
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | adscript: add page (#6432) | 2021-09-02T14:15:33 | [e6cc4006f5fc](https://github.com/tldr-pages/tldr/commit/e6cc4006f5fc27767f730123cfd524a158ace138)

