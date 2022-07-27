---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "where, TLDR Pages"
description: "where, 显示与搜索模式匹配的文件的位置。"
categories: "windows"
---
> 在默认情况下，搜索是在当前目录和 PATH 环境变量指定的路径中执行的。

> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/where>.

- 显示匹配的文件的位置：

```bash
where 文件模式
```

- 显示匹配的文件的位置、大小和日期：

```bash
where /T 文件模式
```

- 在指定的路径下递归搜索要匹配的文件：

```bash
where /R 目录的路径 文件模式
```

- 只返回退出代码，不显示匹配文件列表：

```bash
where /Q 文件模式
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | where: add Chinese translation | 2019-03-12T12:56:23 | [da9ea7b1f56a](https://github.com/tldr-pages/tldr/commit/da9ea7b1f56a510d08b09fbb7877a94e98884e63)

