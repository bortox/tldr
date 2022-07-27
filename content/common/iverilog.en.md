---
author: ['bl-ue', 'Ashish Shenoy']
date: 1607722048
title: "iverilog, TLDR Pages"
description: "iverilog, Preprocesses and compiles Verilog HDL (IEEE-1364) code, into executable programs for simulation."
categories: "common"
---
> More information: <http://iverilog.icarus.com/>.

- Compile a source file into an executable:

```bash
iverilog source.v -o executable
```

- Also display all warnings:

```bash
iverilog source.v -Wall -o executable
```

- Compile and run explicitly using the VVP runtime:

```bash
iverilog -o executable -tvvp source.v
```

- Compile using Verilog library files from a different path:

```bash
iverilog source.v -o executable -Ipath/to/library_directory
```

- Preprocess Verilog code without compiling:

```bash
iverilog -E source.v
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Ashish Shenoy](mailto:ashish1shenoy@gmail.com) | iverilog: add page (#3303) | 2019-10-03T22:35:53 | [cb3dde850285](https://github.com/tldr-pages/tldr/commit/cb3dde850285987997a61c70a208f69ee310aa92)

