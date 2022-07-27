---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "fc, TLDR Pages"
description: "fc, 比较两个文件或文件集之间的差异。"
categories: "windows"
---
> 使用通配符（*）来比较文件集。

> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/fc>.

- 比较两个指定的文件：

```bash
fc 文件 1 的路径 文件 2 的路径
```

- 比较时不区分大小写：

```bash
fc /c 文件 1 的路径 文件 2 的路径
```

- 将文件作为 Unicode 文本来进行比较：

```bash
fc /u 文件 1 的路径 文件 2 的路径
```

- 将文件作为 ASCII 文本来进行比较：

```bash
fc /l 文件 1 的路径 文件 2 的路径
```

- 将文件作为二进制来比较：

```bash
fc /b 文件 1 的路径 文件 2 的路径
```

- 禁用制表符到空格的扩展：

```bash
fc /t 文件 1 的路径 文件 2 的路径
```

- 压缩空格（制表符和空格）进行比较：

```bash
fc /w 文件 1 的路径 文件 2 的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | fc: add Chinese translation | 2019-03-12T12:56:23 | [1a0de12cd857](https://github.com/tldr-pages/tldr/commit/1a0de12cd857e982ebe3f9def4e5245b78600dd1)

