---
author: ['marchersimon']
date: 1633112881
title: "netstat, TLDR Pages"
description: "netstat, 显示与网络相关的信息，如打开的连接、打开的套接字端口等。"
categories: "common"
---
> 更多信息：<https://man7.org/linux/man-pages/man8/netstat.8.html>.

- 列出所有端口：

```bash
netstat -a
```

- 列出所有被侦听端口：

```bash
netstat -l
```

- 列出侦听的 TCP 端口：

```bash
netstat -t
```

- 显示监听给定协议监听的 PID 和程序名：

```bash
netstat -p 协议
```

- 打印路由表：

```bash
netstat -nr
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

