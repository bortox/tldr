---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'meowmeowcat']
date: 1636919159
title: "scutil"
description: "scutil, 管理系统配置参数。"
categories: "osx"
---
> 设置配置时必须是 root 权限。

> 更多信息：<https://ss64.com/osx/scutil.html>.

- 显示 DNS 配置：

```bash
scutil --dns
```

- 显示代理配置：

```bash
scutil --proxy
```

- 获取计算机名称：

```bash
scutil --get ComputerName
```

- 设置计算机名称：

```bash
sudo scutil --set ComputerName 我的计算机名
```

- 获取主机名（HostName）：

```bash
scutil --get HostName
```

- 设置主机名：

```bash
scutil --set HostName hostname
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | scutil: add Chinese translation | 2019-03-15T12:47:29 | [e68aeab79434](https://github.com/tldr-pages/tldr/commit/e68aeab7943482fa67bab9e8d1cee8b5663bcde5)

