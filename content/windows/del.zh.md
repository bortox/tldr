---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "del"
description: "del, 删除一个或多个文件。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/del>.

- 删除一个或多个以空格分隔的文件：

```bash
del 文件 文件 ..
```

- 在删除每个文件之前提示确认：

```bash
del 文件 /p
```

- 强制删除只读文件：

```bash
del 文件 /f
```

- 递归删除所有子目录中的文件：

```bash
del 文件 /s
```

- 在基于全局通配符删除文件时不提示确认：

```bash
del 文件 /q
```

- 显示帮助和所有的属性列表：

```bash
del /?
```

- 根据指定的属性删除文件：

```bash
del 文件 /a 属性
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | del: add Chinese translation | 2019-03-12T12:56:23 | [85dfc7f5f5b2](https://github.com/tldr-pages/tldr/commit/85dfc7f5f5b25baaa85a29b0cfcbf3c1b7c7c472)

