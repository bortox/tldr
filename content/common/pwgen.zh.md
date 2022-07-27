---
author: ['marchersimon']
date: 1632060820
title: "pwgen, TLDR Pages"
description: "pwgen, 生成可拼写发音的密码。"
categories: "common"
---
- 生成指定长度的随机密码：

```bash
pwgen -y 长度
```

- 生成安全、难以记忆的密码：

```bash
pwgen -s 长度
```

- 生成至少包含一个大写字母的密码：

```bash
pwgen -c 长度
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

