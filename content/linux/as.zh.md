---
author: ['bl-ue', 'Marco Bonelli', 'Stig124', 'Ein Verne', 'lmh', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "as, TLDR Pages"
description: "as, 一个可移植的 GUN 汇编器。"
categories: "linux"
---
> 主要用于汇编`gcc`的输出，以供链接器`ld`使用。

> 更多信息：<https://manned.org/as>.

- 汇编一个文件，输出为 a.out：

```bash
as 文件.s
```

- 汇编文件，并指定输出文件：

```bash
as 文件.s -o 输出.o
```

- 通过跳过空格和注释的预处理过程来更快的产生输出文件（只应该用于可信任的编译器的输出）：

```bash
as -f 文件.s
```

- 将给定路径添加到目录列表，来搜索.include 指令指定的文件：

```bash
as -I 目录路径 文件.s
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | archey, arp-scan, as, aspell, at: remove execute permission (#5243) | 2021-02-11T14:08:59 | [de72bdb4f8da](https://github.com/tldr-pages/tldr/commit/de72bdb4f8dab69bee04f4cd80bdab935c90f654)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | refactor: fix newlines removing carriage returns (#2880) | 2019-04-10T11:49:16 | [51e3430a3883](https://github.com/tldr-pages/tldr/commit/51e3430a3883b604de4f986f80368e9252c65b94)
[lmh](mailto:hugue_liu@yahoo.com) | as: add Chinese translation. | 2019-02-13T16:10:51 | [b1306156df75](https://github.com/tldr-pages/tldr/commit/b1306156df75c055fb6a96432f3edf1c09a15389)

