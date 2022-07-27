---
author: ['Guilherme Leobas', 'Waldir Pimenta', 'Schneider', 'Marco Bonelli', 'Ruben Vereecken', 'pixel']
date: 1631217354
title: "clang, TLDR Pages"
description: "clang, Compiler for C, C++, and Objective-C source files. Can be used as a drop-in replacement for GCC."
categories: "common"
---
> More information: <https://clang.llvm.org/docs/ClangCommandLineReference.html>.

- Compile a source code file into an executable binary:

```bash
clang input_source.c -o output_executable
```

- Activate output of all errors and warnings:

```bash
clang input_source.c -Wall -o output_executable
```

- Include libraries located at a different path than the source file:

```bash
clang input_source.c -o output_executable -Iheader_path -Llibrary_path -llibrary_name
```

- Compile source code into LLVM Intermediate Representation (IR):

```bash
clang -S -emit-llvm file.c -o file.ll
```

- Compile source code without linking:

```bash
clang -c input_source.c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | clang: add -c example (#6494) | 2021-09-09T21:55:54 | [222f3e613064](https://github.com/tldr-pages/tldr/commit/222f3e6130649b6b7da197308c77b0fe026694d4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | clang.md: add homepage | 2019-04-15T01:35:17 | [1abf8f562a92](https://github.com/tldr-pages/tldr/commit/1abf8f562a92c25c31b311d294c14b50706abe6b)
[Guilherme Leobas](mailto:guilhermeleobas@gmail.com) | clang: add -emit-llvm example (#2499) | 2018-10-28T18:04:44 | [5f67df146bff](https://github.com/tldr-pages/tldr/commit/5f67df146bffb10a328bfdeb456a71810aa1ad54)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | add clang | 2015-08-04T20:18:34 | [3407a4ae6526](https://github.com/tldr-pages/tldr/commit/3407a4ae652604bfa359a1d4161e8a456f6f43cb)

