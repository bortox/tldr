---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "reg compare, TLDR Pages"
description: "reg compare, 比较注册表中的键和值。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/reg-compare>.

- 比较两个键中的所有值：

```bash
reg compare 第一个键名 第二个键名
```

- 比较两个键中指定的值：

```bash
reg compare 第一个键名 第二个键名 /v 值
```

- 比较两个键中的所有子键和值：

```bash
reg compare 第一个键名 第二个键名 /s
```

- 仅输出指定键之间匹配的结果：

```bash
reg compare 第一个键名 第二个键名 /os
```

- 输出两个键之间的匹配和差异：

```bash
reg compare 第一个键名 第二个键名 /oa
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | reg-compare: add Chinese translation | 2019-03-12T12:56:23 | [bb2ef056f233](https://github.com/tldr-pages/tldr/commit/bb2ef056f233dae33002582d78d49efb87119987)

