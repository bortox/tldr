---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "choco install"
description: "choco install, 使用 Chocolatey 下载一个或多个包。"
categories: "windows"
---
> 更多信息：<https://chocolatey.org/docs/commands-install>.

- 安装一个或多个用空格分隔的软件包：

```bash
choco install 包名 包名 ..
```

- 从一个自定义的配置文件中安装包：

```bash
choco install 配置文件的路径
```

- 安装一个特定的 "nuspec" 或 "nupkg" 文件：

```bash
choco install 文件的路径
```

- 安装一个指定版本的包：

```bash
choco install 包名 --version 版本号
```

- 允许安装一个包的多个版本：

```bash
choco install 包名 --allow-multiple
```

- 自动确认所有提示：

```bash
choco install 包名 --yes
```

- 从自定义的源处获取包：

```bash
choco install 包名 --source 源 URL|别名
```

- 提供一个用户名和密码来进行验证：

```bash
choco install 包名 --user 用户名 --password 密码
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | choco-install: add Chinese translation | 2019-03-12T12:56:23 | [2bfa70ae18f4](https://github.com/tldr-pages/tldr/commit/2bfa70ae18f47a1abc7d0b8d2783ec2ac3fa3abd)

