---
author: ['Amin Yahyaabadi']
date: 1638356531
title: "vcvarsall, TLDR Pages"
description: "vcvarsall, Setup the environment variables required for using the Microsoft Visual Studio tools from the command line."
categories: "windows"
---
> The path of `vcvarsall` for a certain Visual Studio installation can be found using `vswhere`.

> More information: <https://docs.microsoft.com/cpp/build/building-on-the-command-line>.

- Setup the environment for native x64:

```bash
vcvarsall x64
```

- Setup the environment for cross-compiled native x86 from the x64 host:

```bash
vcvarsall x64_x86
```

- Setup the environment for cross-compiled native Arm x64 from the x64 host:

```bash
vcvarsall x64_arm64
```

- Setup the environment for native UWP x64:

```bash
vcvarsall x64 uwp
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Amin Yahyaabadi](mailto:aminyahyaabadi74@gmail.com) | vcvarsall: add page (#7439) | 2021-12-01T12:02:11 | [1025fec2709a](https://github.com/tldr-pages/tldr/commit/1025fec2709affd30384f1257caaefebf51c73f1)

