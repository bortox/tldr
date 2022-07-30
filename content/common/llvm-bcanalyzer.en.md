---
author: ['pixel']
date: 1632061582
title: "llvm-bcanalyzer"
description: "llvm-bcanalyzer, LLVM Bitcode (`.bc`) analyzer."
categories: "common"
---
> More information: <https://llvm.org/docs/CommandGuide/llvm-bcanalyzer.html>.

- Print statistics about a Bitcode file:

```bash
llvm-bcanalyzer path/to/file.bc
```

- Print an SGML representation and statistics about a Bitcode file:

```bash
llvm-bcanalyzer -dump path/to/file.bc
```

- Read a Bitcode file from `stdin` and analyze it:

```bash
cat path/to/file.bc | llvm-bcanalyzer
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | llvm-bcanalyzer: add page (#6558) | 2021-09-19T16:26:22 | [9040e5a17193](https://github.com/tldr-pages/tldr/commit/9040e5a17193d968dad62f135a45e247edf9f5d5)

