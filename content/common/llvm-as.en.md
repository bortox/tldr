---
author: ['pixel']
date: 1631962392
title: "llvm-as, TLDR Pages"
description: "llvm-as, LLVM Intermediate Representation (`.ll`) to Bitcode (`.bc`) assembler."
categories: "common"
---
> More information: <https://llvm.org/docs/CommandGuide/llvm-as.html>.

- Assemble an IR file:

```bash
llvm-as -o path/to/out.bc path/to/source.ll
```

- Assemble an IR file and include a module hash in the produced Bitcode file:

```bash
llvm-as --module-hash -o path/to/out.bc path/to/source.ll
```

- Read an IR file from `stdin` and assemble it:

```bash
cat path/to/source.ll | llvm-as -o path/to/out.bc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | llvm-as: add page (#6496) | 2021-09-18T12:53:12 | [42030c2c9fb3](https://github.com/tldr-pages/tldr/commit/42030c2c9fb35b97654cb42dceb68931e525de80)

