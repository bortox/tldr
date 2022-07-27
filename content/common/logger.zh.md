---
author: ['Seth Falco', 'marchersimon']
date: 1648358715
title: "logger, TLDR Pages"
description: "logger, 向系统日志增加记录（/var/log/syslog）。"
categories: "common"
---
> 更多信息：<https://manned.org/logger>.

- 向系统日志增加记录：

```bash
logger 消息内容
```

- 从 stdin 获取输入并记录到系统日志 syslog：

```bash
echo 记录内容 | logger
```

- 将输出发送到在给定端口上运行的远程系统日志服务器。默认端口为 514：

```bash
echo 记录内容 | logger -h 服务器名 -P 端口
```

- 对记录的每一行使用特定的标签。默认值是登录用户的名：

```bash
echo 记录内容 | logger -t 标签
```

- 以给定的错误等级记录消息。默认是 `user.notice`. 使用 `man logger` 查询所有可选等级：

```bash
echo 记录内容 | logger -p user.warning
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

