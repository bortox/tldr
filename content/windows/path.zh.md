---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "path, TLDR Pages"
description: "path, 显示或设置可执行文件的搜索路径。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/path>.

- 显示当前的路径：

```bash
path
```

- 将路径设置为一个或多个以分号分隔的目录：

```bash
path 目录的路径 1[; 目录的路径 2]
```

- 将新的目录添加到源路径后：

```bash
path 目录的路径;%path%
```

- 将命令提示符设置为仅搜索当前目录中的可执行文件：

```bash
path ;
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | path: add Chinese translation | 2019-03-12T12:56:23 | [f61ef1901976](https://github.com/tldr-pages/tldr/commit/f61ef19019768f9e1d144589b8092476e1f0d98b)

