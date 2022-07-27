---
author: ['marchersimon', 'syleung']
date: 1633351190
title: "sshuttle, TLDR Pages"
description: "sshuttle, 通过 ssh 连接传输流量的透明代理服务器。"
categories: "common"
---
> 不需要管理员或远程 ssh 服务器上的任何特殊设置。

> 更多信息：<https://manned.org/sshuttle>.

- 通过远程 ssh 服务器转发所有 IPv4 TCP 流量：

```bash
sshuttle --remote=用户名@服务器名 0.0.0.0/0
```

- 转发所有 IPv4 TCP 和 DNS 流量：

```bash
sshuttle --dns --remote=用户名@服务器名 0.0.0.0/0
```

- 使用 tproxy 方法转发所有 IPv4 和 IPv6 流量：

```bash
sudo sshuttle --method=tproxy --remote=用户名@服务器名 0.0.0.0/0 ::/0 --exclude=你本地 IP 地址 --exclude=SSH 服务器的 IP 地址
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

