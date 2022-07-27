---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "driverquery, TLDR Pages"
description: "driverquery, 显示已安装设备驱动程序的信息。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/driverquery>.

- 显示所有已安装设备驱动程序的列表：

```bash
driverquery
```

- 以指定格式显示驱动程序的列表：

```bash
driverquery /fo table|list|csv
```

- 显示带有列的驱动程序列表，以表明它们是否已签名：

```bash
driverquery /si
```

- 排除输出列表中的标题：

```bash
driverquery /nh
```

- 显示远程计算机的驱动程序列表：

```bash
driverquery /s 主机名 /u 用户名 /p 密码
```

- 显示详细信息的驱动程序列表：

```bash
driverquery /v
```

- 显示详细的使用信息：

```bash
driverquery /?
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | driverquery: add Chinese translation | 2019-03-12T12:56:23 | [f109d78223e0](https://github.com/tldr-pages/tldr/commit/f109d78223e0022b5cde7516c2230d0379d920f0)

