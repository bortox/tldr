---
author: ['Benedek Szilvasy', 'CleanMachine1']
date: 1657497846
title: "llc"
description: "llc, Compiles LLVM Intermediate Representation or bitcode to target-specific assembly language."
categories: "common"
---
> More information: <https://www.llvm.org/docs/CommandGuide/llc.html>.

- Compile a bitcode or IR file to an assembly file with the same base name:

```bash
llc path/to/file.ll
```

- Enable all optimizations:

```bash
llc -O3 path/to/input.ll
```

- Output assembly to a specific file:

```bash
llc --output path/to/output.s
```

- Emit fully relocatable, position independent code:

```bash
llc -relocation-model=pic path/to/input.ll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | common/*: fix spelling errors | 2022-07-11T02:04:06 | [e4719999325f](https://github.com/tldr-pages/tldr/commit/e4719999325f611503c2ad1dc7bea3e8ac25f557)
[Benedek Szilvasy](mailto:benedek.szilvasy@gmail.com) | llc: add page (#6711) | 2021-10-11T05:22:39 | [148c5fe9472a](https://github.com/tldr-pages/tldr/commit/148c5fe9472a5d29d39325682527053dff302eb1)

