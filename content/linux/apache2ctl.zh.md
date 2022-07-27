---
author: ['千玄子', 'marchersimon']
date: 1633112881
title: "apache2ctl, TLDR Pages"
description: "apache2ctl, Apache HTTP web 服务器命令行管理工具。"
categories: "linux"
---
> 基于 Debian 的操作系统自带该命令，基于 RHEL 的查看 `httpd`。

> 更多信息：<https://manpages.debian.org/latest/apache2/apache2ctl.8.en.html>.

- 启动 Apache 守护进程。如果已运行则发送一个消息：

```bash
sudo apache2ctl start
```

- 关闭 Apache 守护进程：

```bash
sudo apache2ctl stop
```

- 重启 Apache 守护进程：

```bash
sudo apache2ctl restart
```

- 检查配置文件语法：

```bash
sudo apache2ctl -t
```

- 列出已加载模块：

```bash
sudo apache2ctl -M
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

