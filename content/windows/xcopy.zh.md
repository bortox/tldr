---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "xcopy, TLDR Pages"
description: "xcopy, 复制文件和目录树。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/xcopy>.

- 复制文件到指定的路径：

```bash
xcopy 被复制的目录路径 目标路径
```

- 列出在复制前将要被复制的文件：

```bash
xcopy 文件或目录的路径 目标路径 /p
```

- 仅复制目录结构，不包括文件：

```bash
xcopy 文件或目录的路径 目标路径 /t
```

- 复制时包含空目录：

```bash
xcopy 文件或目录的路径 目标路径 /e
```

- 复制文件时保留 ACL 信息：

```bash
xcopy 文件或目录的路径 目标路径 /o
```

- 网络连接丢失时允许恢复：

```bash
xcopy 文件或目录的路径 目标路径 /z
```

- 当文件存在于目标路径中时禁用提示：

```bash
xcopy 文件或目录的路径 目标路径 /y
```

- 显示详细的使用帮助：

```bash
xcopy /?
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | xcopy: add Chinese translation | 2019-03-12T12:56:23 | [f172b9ed4a55](https://github.com/tldr-pages/tldr/commit/f172b9ed4a553ae402461573b1226d1308cc0e87)

