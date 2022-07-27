---
author: ['Schneider', 'bl-ue', 'Ein Verne', 'Starccy', 'marchersimon']
date: 1633112881
title: "choco upgrade, TLDR Pages"
description: "choco upgrade, 使用 Chocolatey 升级一个或多个包。"
categories: "windows"
---
> 更多信息：<https://chocolatey.org/docs/commands-upgrade>.

- 升级一个或多个用空格分隔的软件包：

```bash
choco upgrade 包名 包名 ..
```

- 将一个包升级到指定版本：

```bash
choco upgrade 包名 --version 版本号
```

- 升级全部包：

```bash
choco upgrade all
```

- 升级除指定的用逗号分隔的包之外的所有包：

```bash
choco upgrade all --except "包名 , 包名 .."
```

- 自动确认所有提示：

```bash
choco upgrade 包名 --yes
```

- 从自定义源处升级包：

```bash
choco upgrade 包名 --source 源 URL|别名
```

- 提供一个用户名和密码来进行验证：

```bash
choco upgrade 包 --user 用户名 --password 密码
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Schneider](mailto:lucas.schneider@sap.com) | choco-upgrade: modify examples to look similar to other choco | 2020-02-05T19:25:07 | [ea5ccf169488](https://github.com/tldr-pages/tldr/commit/ea5ccf169488f8dc3217e4042508b9ee1acbc40e)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | choco-upgrade: add Chinese translation | 2019-03-12T12:56:23 | [3d83dbd46db1](https://github.com/tldr-pages/tldr/commit/3d83dbd46db12a2371fdf239fb226e0edee38916)

