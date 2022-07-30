---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "choco uninstall"
description: "choco uninstall, 使用 Chocolatey 卸载一个或多个包。"
categories: "windows"
---
> 更多信息：<https://chocolatey.org/docs/commands-uninstall>.

- 卸载一个或多个用空格分隔的软件包：

```bash
choco uninstall 包名 『包名』 ..
```

- 卸载一个指定版本的包：

```bash
choco uninstall 包名 --version 版本号
```

- 自动确认所有提示：

```bash
choco uninstall 包名 --yes
```

- 卸载时同时删除其所有的依赖：

```bash
choco uninstall 包名 --remove-dependencies
```

- 卸载全部包：

```bash
choco uninstall all
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | choco-uninstall: add Chinese translation | 2019-03-12T12:56:23 | [4c35fd2ae0e3](https://github.com/tldr-pages/tldr/commit/4c35fd2ae0e3523ec5215465a6e0a05b6eadc0b5)

