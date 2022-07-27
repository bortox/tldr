---
author: ['Jake Vossen']
date: 1623096350
title: "llvm-dis, TLDR Pages"
description: "llvm-dis, Converts LLVM bitcode files into human-readable LLVM Intermediate Representation (IR)."
categories: "common"
---
> More information: <https://www.llvm.org/docs/CommandGuide/llvm-dis.html>.

- Convert a bitcode file as LLVM IR and write the result to stdout:

```bash
llvm-dis path/to/input.bc -o -
```

- Convert a bitcode file to an LLVM IR file with the same filename:

```bash
llvm-dis path/to/file.bc
```

- Convert a bitcode file to LLVM IR, writing the result to the specified file:

```bash
llvm-dis path/to/input.bc -o path/to/output.ll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jake Vossen](mailto:jake@vossen.dev) | llvm-dis: add page (#6049) | 2021-06-07T22:05:50 | [542b4bf1c397](https://github.com/tldr-pages/tldr/commit/542b4bf1c3979862bac4950cc4934523c6004d57)

