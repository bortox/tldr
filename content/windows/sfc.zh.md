---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "sfc, TLDR Pages"
description: "sfc, 扫描 Windows 系统文件的完整性。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/sfc>.

- 显示命令的使用方法：

```bash
sfc
```

- 扫描所有的系统文件，如果可能的话，修复所有出现的问题：

```bash
sfc /scannow
```

- 扫描系统文件，但不修复出现的问题：

```bash
sfc /verifyonly
```

- 扫描指定的文件，如果可能的话，修复所有出现的问题：

```bash
sfc /scanfile=文件的路径
```

- 扫描指定的文件，但不修复出现的问题：

```bash
sfc /verifyfile=文件的路径
```

- 当离线修复时，指定引导目录：

```bash
sfc /offbootdir=目录的路径
```

- 当离线修复时，指定 Windows 目录：

```bash
sfc /offwindir=文件的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | sfc: add Chinese translation | 2019-03-12T12:56:23 | [2ea1df8c519f](https://github.com/tldr-pages/tldr/commit/2ea1df8c519f02aa6fce734661a83bc1753f105e)

