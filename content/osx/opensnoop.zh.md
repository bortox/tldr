---
author: ['wizarot', 'bl-ue', 'Ein Verne']
date: 1627893669
title: "opensnoop, TLDR Pages"
description: "opensnoop, 跟踪系统中打开的文件标识符。"
categories: "osx"
---
- 输出当前系统内被打开的所有文件：

```bash
sudo opensnoop
```

- 跟踪给定进程名，打开的所有文件：

```bash
sudo opensnoop -n 进程名
```

- 跟踪给定 PID（进程号），打开的所有文件：

```bash
sudo opensnoop -p PID 进程号
```

- 跟踪打开了指定文件的继承：

```bash
sudo opensnoop -f 路径 / 文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | opensnoop: add Chinese translation | 2019-03-15T12:47:29 | [920958cf2009](https://github.com/tldr-pages/tldr/commit/920958cf20098538a55e92fff63062f42e11fe39)

