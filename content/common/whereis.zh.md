---
author: ['derNiklaas', 'marchersimon']
date: 1633404950
title: "whereis"
description: "whereis, 找到命令的二进制，源文件和手册文件。"
categories: "common"
---
> 更多信息：<https://manned.org/whereis>.

- 找到 `ssh` 命令的二进制、源文件和手册页：

```bash
whereis ssh
```

- 查找 `ls` 命令的二进制和手册页：

```bash
whereis -bm ls
```

- 找到 `gc` 的源文件和 `git` 的手册页：

```bash
whereis -s gcc -m git
```

- 仅在 /usr/bin/ 目录中查找 `gcc` 的二进制文件：

```bash
whereis -b -B /usr/bin/ -f gcc
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | whereis, xar, yank: move to common (#6552) | 2021-09-19T02:59:20 | [e94e6af88289](https://github.com/tldr-pages/tldr/commit/e94e6af88289f26bf25c85b45971f240f56d8672)

