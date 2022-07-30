---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "taskkill"
description: "taskkill, 按进程 id 或进程名终止进程。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/taskkill>.

- 通过进程 id 终止进程：

```bash
taskkill /pid 进程 id
```

- 通过进程名终止进程：

```bash
taskkill /im 进程名
```

- 强制终止一个指定的进程：

```bash
taskkill /pid 进程名 /f
```

- 终止一个进程及其子进程：

```bash
taskkill /im 进程名 /t
```

- 终止远程计算机上的进程：

```bash
taskkill /pid 进程 id /s 远程主机名
```

- 显示命令的帮助信息：

```bash
taskkill /?
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | taskkill: add Chinese translation | 2019-03-12T12:56:23 | [1c79b91aa58f](https://github.com/tldr-pages/tldr/commit/1c79b91aa58f68244152a0153777b68abc7dc20d)

