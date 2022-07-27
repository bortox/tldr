---
author: ['Agniva De Sarker', 'Lucas Gabriel Schneider', 'Benedek Szilvasy']
date: 1636231963
title: "wasm2c, TLDR Pages"
description: "wasm2c, Convert a file from the WebAssembly binary format to a C source file and header."
categories: "common"
---
> More information: <https://github.com/WebAssembly/wabt>.

- Convert a file to a C source file and header and display it to the console:

```bash
wasm2c file.wasm
```

- Write the output to a given file (`file.h` gets additionally generated):

```bash
wasm2c file.wasm -o file.c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Benedek Szilvasy](mailto:benedek.szilvasy@gmail.com) | wasm-objdump, wasm-opt, wasm2c, wasm2wat: add link (#7269) | 2021-11-06T21:52:43 | [8287fc667741](https://github.com/tldr-pages/tldr/commit/8287fc667741f492c7f7839a7c10aaff487a6151)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | wasm2c: add page (#2375) | 2018-10-02T11:23:43 | [0233b61e1153](https://github.com/tldr-pages/tldr/commit/0233b61e1153a40382bad842b0966d9926e9c862)

