---
author: ['Agniva De Sarker', 'Benedek Szilvasy']
date: 1636231963
title: "wasm-objdump, TLDR Pages"
description: "wasm-objdump, Display information from WebAssembly binaries."
categories: "common"
---
> More information: <https://github.com/WebAssembly/wabt>.

- Display the section headers of a given binary:

```bash
wasm-objdump -h file.wasm
```

- Display the entire disassembled output of a given binary:

```bash
wasm-objdump -d file.wasm
```

- Display the details of each section:

```bash
wasm-objdump --details file.wasm
```

- Display the details of a given section:

```bash
wasm-objdump --section 'import' --details file.wasm
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Benedek Szilvasy](mailto:benedek.szilvasy@gmail.com) | wasm-objdump, wasm-opt, wasm2c, wasm2wat: add link (#7269) | 2021-11-06T21:52:43 | [8287fc667741](https://github.com/tldr-pages/tldr/commit/8287fc667741f492c7f7839a7c10aaff487a6151)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | wasm-objdump: add page (#2373) | 2018-10-03T18:43:11 | [c115541a3643](https://github.com/tldr-pages/tldr/commit/c115541a36430f7f5b728a9ac0c824565dc06bcf)

