---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "choco list, TLDR Pages"
description: "choco list, 使用 Chocolatey 显示包列表。"
categories: "windows"
---
> 更多信息：<https://chocolatey.org/docs/commands-list>.

- 列出所有可用的包：

```bash
choco list
```

- 列出所有本地已安装的包：

```bash
choco list --local-only
```

- 显示包含本地程序的列表：

```bash
choco list --include-programs
```

- 只显示已批准的包：

```bash
choco list --approved-only
```

- Specify a custom source to display packages from 指定一个源来显示包列表：

```bash
choco list --source 源 URL|别名
```

- 提供一个用户名和密码来进行验证：

```bash
choco list --user 用户名 --password 密码
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | choco-list: add Chinese translation | 2019-03-12T12:56:23 | [b861fad05602](https://github.com/tldr-pages/tldr/commit/b861fad0560264b2608aac81f943a2bf9dbfd6ea)

