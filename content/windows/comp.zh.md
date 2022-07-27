---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "comp, TLDR Pages"
description: "comp, 比较两个文件或文件集的内容。"
categories: "windows"
---
> 使用通配符（*）来比较文件集。

> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/comp>.

- 交互式比较文件：

```bash
comp
```

- 比较两个指定的文件：

```bash
comp 文件 1 的路径 文件 2 的路径
```

- 比较两个文件集：

```bash
comp 目录 1/* 目录 2/*
```

- 以十进制格式显示差异：

```bash
comp /d 文件 1 的路径 文件 2 的路径
```

- 以 ASCII 字符显示差异：

```bash
comp /a 文件 1 的路径 文件 2 的路径
```

- 显示不同的行数：

```bash
comp /l 文件 1 的路径 文件 2 的路径
```

- 比较文件时不区分大小写：

```bash
comp /c 文件 1 的路径 文件 2 的路径
```

- 只比较每个文件前 5 行的内容：

```bash
comp /n=5 文件 1 的路径 文件 2 的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | comp: add Chinese translation | 2019-03-12T12:56:23 | [3fb23e0f6f0a](https://github.com/tldr-pages/tldr/commit/3fb23e0f6f0a189d7386207abc2dffa567ef485d)

