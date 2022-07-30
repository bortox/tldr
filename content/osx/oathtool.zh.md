---
author: ['wizarot', 'bl-ue']
date: 1627893669
title: "oathtool"
description: "oathtool, OATH 一次性密码工具。"
categories: "osx"
---
- 生成 TOTP 令牌（行为类似于 Google Authenticator）：

```bash
oathtool --totp --base32 密码
```

- 根据给定时间产生特定的 TOTP 令牌：

```bash
oathtool --totp --now 2004-02-29 16:21:42 --base32 密码
```

- 验证 TOTP 令牌：

```bash
oathtool --totp --base32 密码 令牌
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[wizarot](mailto:wizarot@qq.com) | oathtool: add Chinese translation | 2019-03-15T12:47:29 | [a7f635fbe36b](https://github.com/tldr-pages/tldr/commit/a7f635fbe36b0e17958db9bf63196d9ab3446ce2)

