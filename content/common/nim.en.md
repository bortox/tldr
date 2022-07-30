---
author: ['Hugo Locurcio', 'pxgamer']
date: 1559676580
title: "nim"
description: "nim, The Nim compiler."
categories: "common"
---
> Processes, compiles and links Nim language source files.

> More information: <https://nim-lang.org>.

- Compile a source file:

```bash
nim compile file.nim
```

- Compile and run a source file:

```bash
nim compile -r file.nim
```

- Compile a source file with release optimizations enabled:

```bash
nim compile -d:release file.nim
```

- Build a release binary optimized for low file size:

```bash
nim compile -d:release --opt:size file.nim
```

- Generate HTML documentation for a module (output will be placed in the current directory):

```bash
nim doc file.nim
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | nim: add link to homepage | 2019-06-04T21:29:40 | [b50f724a8617](https://github.com/tldr-pages/tldr/commit/b50f724a861785e0b61f25bc6e6a04239b3b192a)
[Hugo Locurcio](mailto:hugo.locurcio@hugo.pro) | nim: add page (#2207) | 2018-07-21T18:56:19 | [15f352df24e4](https://github.com/tldr-pages/tldr/commit/15f352df24e44f6f8a7cc7cdba80513447497fca)

