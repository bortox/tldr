---
author: ['Gabriel Totev', 'sebastientinel', 'pxgamer']
date: 1603905583
title: "nasm"
description: "nasm, The Netwide Assembler, a portable 80x86 assembler."
categories: "common"
---
> More information: <https://nasm.us>.

- Assemble `source.asm` into a binary file `source`, in the (default) raw binary format:

```bash
nasm source.asm
```

- Assemble `source.asm` into a binary file `output_file`, in the specified format:

```bash
nasm -f format source.asm -o output_file
```

- List valid output formats (along with basic nasm help):

```bash
nasm -hf
```

- Assemble and generate an assembly listing file:

```bash
nasm -l list_file source.asm
```

- Add a directory (must be written with trailing slash) to the include file search path before assembling:

```bash
nasm -i path/to/include_dir/ source.asm
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[pxgamer](mailto:owzie123@gmail.com) | nasm: add link to homepage | 2019-06-04T21:29:40 | [db1934288143](https://github.com/tldr-pages/tldr/commit/db1934288143bf1ec5597a28b9262249d81cdad1)
[Gabriel Totev](mailto:gttotev8@gmail.com) | nasm: add page (#1401) | 2017-06-10T01:03:16 | [1d2cbd0f07a4](https://github.com/tldr-pages/tldr/commit/1d2cbd0f07a475ef70aefe2ea1c166e943127574)

