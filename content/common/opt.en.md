---
author: ['Guilherme Leobas', 'pxgamer', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1656325392
title: "opt"
description: "opt, A tool that takes LLVM source files and runs specified optimizations and/or analysis on them."
categories: "common"
---
> More information: <https://llvm.org/docs/CommandGuide/opt.html>.

- Run an optimization or analysis on a bitcode file:

```bash
opt -passname path/to/file.bc -S -o file_opt.bc
```

- Output the Control Flow Graph of a function to a `.dot` file:

```bash
opt -dot-cfg -S path/to/file.bc -disable-output
```

- Optimize the program at level 2 and output the result to another file:

```bash
opt -O2 path/to/file.bc -S -o path/to/output_file.bc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | opt: add link to homepage | 2019-06-04T21:29:40 | [968a65654615](https://github.com/tldr-pages/tldr/commit/968a65654615b24baf34205c9b81d88da600ef2f)
[Guilherme Leobas](mailto:guilhermeleobas@gmail.com) | opt: add page (#2527) | 2018-11-01T13:25:03 | [244adaf4001f](https://github.com/tldr-pages/tldr/commit/244adaf4001f1645b2f423d1f32680df2799e64b)

