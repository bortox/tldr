---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "choco pin"
description: "choco pin, 使用 Chocolatey 将一个包固定到指定的版本。"
categories: "windows"
---
> 被固定版本的包会在更新时自动忽略。

> 更多信息：<https://chocolatey.org/docs/commands-pin>.

- 显示被固定的包以及他们对应的版本号：

```bash
choco pin list
```

- 将一个包固定至当前版本：

```bash
choco pin add --name 包名
```

- 将一个包固定直指定的版本：

```bash
choco pin add --name 包名 --version 版本号
```

- 移除指定包的固定状态：

```bash
choco pin remove --name 包名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | choco-pin: add Chinese translation | 2019-03-12T12:56:23 | [71d0384c7070](https://github.com/tldr-pages/tldr/commit/71d0384c70706e2c26a79b67e92b33a6226461fc)

