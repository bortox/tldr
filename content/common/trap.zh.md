---
author: ['Seth Falco', 'marchersimon']
date: 1648358715
title: "trap"
description: "trap, 在进程或操作系统接收到信号后自动执行命令。"
categories: "common"
---
> 可用于对用户中断或其他操作执行清理。

> 更多信息：<https://manned.org/trap>.

- 列出设置 trap 的可用信号：

```bash
trap -l
```

- 列出当前 shell 程序的活动 trap 程序：

```bash
trap -p
```

- 设置 trap 以在检测到一个或多个信号时执行命令：

```bash
trap 'echo "检测到信号 SIGHUP"' SIGHUP
```

- 移除活动 trap：

```bash
trap - SIGHUP SIGINT
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

