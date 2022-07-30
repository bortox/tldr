---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "tasklist"
description: "tasklist, 显示本地或远程计算机上当前正在运行的进程的列表。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/tasklist>.

- 显示当前正在运行的进程：

```bash
tasklist
```

- 使用指定的格式显示当前进程列表：

```bash
tasklist /fo table|list|csv
```

- 已匹配的方式（.exe, .dll）显示当前运行的进程：

```bash
tasklist /m 匹配模式
```

- 显示在远程计算机上运行的进程：

```bash
tasklist /s 远程主机名 /u 用户名 /p 密码
```

- 显示每个进程中的服务信息：

```bash
tasklist /svc
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | tasklist: add Chinese translation | 2019-03-12T12:56:23 | [a8f0b954fb70](https://github.com/tldr-pages/tldr/commit/a8f0b954fb707b9af4482ae8138048e9a9f57990)

