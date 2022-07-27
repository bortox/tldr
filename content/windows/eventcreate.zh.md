---
author: ['bl-ue', 'Ein Verne', 'Guido Lena Cota', 'Starccy', 'marchersimon']
date: 1633112881
title: "eventcreate, TLDR Pages"
description: "eventcreate, 在事件日志中创建自定义条目。"
categories: "windows"
---
> 事件 ID 可以是 1 到 1000 之间的任意数值。

> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/eventcreate>.

- 在日志中创建一个具有给定 id（1-1000）的新事件：

```bash
eventcreate /t success|error|warning|information /id id /d "消息"
```

- 在特定事件日志中创建事件：

```bash
eventcreate /l 日志名 /t 类型 /id id /d "消息"
```

- 为新创建的事件指定来源：

```bash
eventcreate /so 来源名 /t 类型 /id id /d "消息"
```

- 在远程计算机的事件日志中创建事件：

```bash
eventcreate /s 主机名 /u 用户名 /p 密码 /t 类型 /id id /d "消息"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | eventcreate: add Chinese translation | 2019-03-12T12:56:23 | [fed02eef4760](https://github.com/tldr-pages/tldr/commit/fed02eef4760dba2242dc4f93de7738d966cbe24)

