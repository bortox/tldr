---
author: ['Srinivasan R', 'Emily Grace Seville', 'liuderchi', 'Marco Bonelli', 'Ruben Vereecken', 'pxgamer', 'CleanMachine1', 'Cvetomir Denchev']
date: 1646220963
title: "gcc, TLDR Pages"
description: "gcc, Preprocess and compile C and C++ source files, then assemble and link them together."
categories: "common"
---
> More information: <https://gcc.gnu.org>.

- Compile multiple source files into executable:

```bash
gcc path/to/source1.c path/to/source2.c ... --output path/to/output_executable
```

- Allow warnings, debug symbols in output:

```bash
gcc path/to/source.c -Wall -Og --output path/to/output_executable
```

- Include libraries from a different path:

```bash
gcc path/to/source.c --output path/to/output_executable -Ipath/to/header -Lpath/to/library -llibrary_name
```

- Compile source code into Assembler instructions:

```bash
gcc -S path/to/source.c
```

- Compile source code without linking:

```bash
gcc -c path/to/source.c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | g++, gcc: page update (#7821) * Update placeholders: - use "path/to" - join list of placeholders in gcc * Suggest language standard in [...] | 2022-03-02T12:36:03 | [02c427a039d9](https://github.com/tldr-pages/tldr/commit/02c427a039d9940a0bad40b5f97fad6fa5ff7e84)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | gcc: add long flag (#6182) | 2021-07-02T21:38:46 | [4c0aa1ac0cb7](https://github.com/tldr-pages/tldr/commit/4c0aa1ac0cb7541cd982040668faad0d842aa1a2)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | gcc: make page description impersonal. (#3526) | 2019-11-04T02:30:33 | [e5f79d3d2cd5](https://github.com/tldr-pages/tldr/commit/e5f79d3d2cd563f97debc4770c8f21279aab4dfc)
[pxgamer](mailto:owzie123@gmail.com) | gcc: add link to homepage | 2019-06-07T23:58:59 | [18f114758d57](https://github.com/tldr-pages/tldr/commit/18f114758d575f72b7ebe9cfca50b351b8fcf5bc)
[liuderchi](mailto:liuderchi@gmail.com) | gcc: add -c option | 2016-05-21T16:55:03 | [fc32c063cf77](https://github.com/tldr-pages/tldr/commit/fc32c063cf7735203de7244f8e90b32c2d8fba2a)
[Cvetomir Denchev](mailto:cvetomir_denchev@abv.bg) | added gcc option | 2016-03-02T14:57:42 | [f667f90bec70](https://github.com/tldr-pages/tldr/commit/f667f90bec702a8a8dfeb501e70ca827b91cd16e)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Added gcc (C++ compiler) to common | 2015-01-12T12:40:00 | [a557b7064e4b](https://github.com/tldr-pages/tldr/commit/a557b7064e4bcb4355d781bbcb8d1d05a252c001)

