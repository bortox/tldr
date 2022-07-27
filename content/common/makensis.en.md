---
author: ['pxgamer', 'Jan T. Sott']
date: 1559676580
title: "makensis, TLDR Pages"
description: "makensis, Cross-platform compiler for NSIS installers."
categories: "common"
---
> It compiles a NSIS script into a Windows installer executable.

> More information: <https://nsis.sourceforge.io/Docs/Chapter3.html>.

- Compile a NSIS script:

```bash
makensis path/to/file.nsi
```

- Compile a NSIS script in strict mode (treat warnings as errors):

```bash
makensis -WX path/to/file.nsi
```

- Print help for a specific command:

```bash
makensis -CMDHELP command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | makensis: add link to homepage | 2019-06-04T21:29:40 | [3c3b4973be7f](https://github.com/tldr-pages/tldr/commit/3c3b4973be7f836f1f706f900d782ac868ffedcc)
[Jan T. Sott](mailto:jan@idleberg.com) | makensis: add page (#2222) | 2018-07-30T07:45:47 | [14ff9659f04a](https://github.com/tldr-pages/tldr/commit/14ff9659f04a0cb09e10a467bf32f022889f5443)

