---
author: ['Agniva De Sarker', 'Benedek Szilvasy']
date: 1636231963
title: "wasm-opt, TLDR Pages"
description: "wasm-opt, Optimize WebAssembly binary files."
categories: "common"
---
> More information: <https://github.com/webassembly/binaryen>.

- Apply default optimizations and write to a given file:

```bash
wasm-opt -O input.wasm -o output.wasm
```

- Apply all optimizations and write to a given file (takes more time, but generates optimal code):

```bash
wasm-opt -O4 input.wasm -o output.wasm
```

- Optimize a file for size:

```bash
wasm-opt -Oz input.wasm -o output.wasm
```

- Print the textual representation of the binary to console:

```bash
wasm-opt input.wasm --print
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Benedek Szilvasy](mailto:benedek.szilvasy@gmail.com) | wasm-objdump, wasm-opt, wasm2c, wasm2wat: add link (#7269) | 2021-11-06T21:52:43 | [8287fc667741](https://github.com/tldr-pages/tldr/commit/8287fc667741f492c7f7839a7c10aaff487a6151)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | wasm-opt: add page (#2383) | 2018-10-03T18:41:02 | [ffd0b4bee498](https://github.com/tldr-pages/tldr/commit/ffd0b4bee4987392b1d14787f8d5c32adfcf00d5)

