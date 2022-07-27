---
author: ['wizarot', 'meowmeowcat', 'Ein Verne', 'bl-ue']
date: 1642165187
title: "top, TLDR Pages"
description: "top, 显示运行进程的动态实时信息。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/top.html>.

- 执行 top 命令，界面中提供所有选项：

```bash
top
```

- 按内部内存大小排序进程（默认顺序 - 进程 ID）：

```bash
top -o mem
```

- 首先按 CPU 启动顺序排序进程，然后按运行时间排序：

```bash
top -o cpu -O time
```

- 只显示给定用户拥有的进程：

```bash
top -user 用户名
```

- 获取有关交互式命令的帮助（我测试并没看到这个功能）：

```bash
?
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | textutil, top: add link (#7629) | 2022-01-14T13:59:47 | [e2f4d81f6bd4](https://github.com/tldr-pages/tldr/commit/e2f4d81f6bd48fe667d0659b5cb165a2244c9f54)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | top: add Chinese translation | 2019-04-01T22:57:41 | [21fece70d62d](https://github.com/tldr-pages/tldr/commit/21fece70d62d2bb036a98e91ca8ce307a3ca3c71)

