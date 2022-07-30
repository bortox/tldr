---
author: ['Amin Yahyaabadi']
date: 1639130858
title: "vswhere"
description: "vswhere, Locate Visual Studio 2017 and newer installations."
categories: "windows"
---
> More information: <https://github.com/microsoft/vswhere>.

- Find the path of vcvarsall.bat to set environment variables:

```bash
vswhere -products * -latest -prerelease -find **/VC/Auxiliary/Build/vcvarsall.bat
```

- Find the directory of the x64 MSVC compiler (cl.exe, etc):

```bash
vswhere -products * -latest -prerelease -find **/Hostx64/x64/*
```

- Find the directory of Clang bundled with Visual Studio bundled (clang-cl, clang-tidy, etc):

```bash
vswhere -products * -latest -prerelease -find **/Llvm/bin/*
```

- Find the path of `MSBuild.exe`:

```bash
vswhere -products * -latest -prerelease -find MSBuild/**/Bin/MSBuild.exe
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Amin Yahyaabadi](mailto:aminyahyaabadi74@gmail.com) | vswhere: remove invalid quotes in example (#7520) | 2021-12-10T11:07:38 | [5e84bc97dac5](https://github.com/tldr-pages/tldr/commit/5e84bc97dac5c67a1badc49c13cef98334c71fd4)
[Amin Yahyaabadi](mailto:aminyahyaabadi74@gmail.com) | vswhere: add page (#7436) | 2021-11-28T13:10:53 | [5741d4dcf61b](https://github.com/tldr-pages/tldr/commit/5741d4dcf61b89a940793527ce0e2a278e13bc9b)

