---
author: ['千玄子']
date: 1630035519
title: "aurvote"
description: "aurvote, 为 AUR 中的包投票。"
categories: "linux"
---
> 为了投票成功，文件 `~/.config/aurvote` 必须存在并包含你的 AUR 身份凭证。

> 更多信息：<https://github.com/archlinuxfr/aurvote>.

- 交互式创建包含你的 AUR 用户名和密码的 `~/.config/aurvote` 文件：

```bash
aurvote --configure
```

- 为一个或多个 AUR 包投票：

```bash
aurvote package1 package2 ...
```

- 为一个或多个 AUR 包取消投票：

```bash
aurvote --unvote package1 package2 ...
```

- 检查一个或多个 AUR 包是否已投票：

```bash
aurvote --check package1 package2 ...
```

- 查看 `aurvote` 的帮助信息：

```bash
aurvote --help
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

