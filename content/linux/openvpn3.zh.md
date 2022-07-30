---
author: ['Nata Jam']
date: 1645103864
title: "openvpn3"
description: "openvpn3, OpenVPN 3 Linux 客户端。"
categories: "linux"
---
> 更多信息：<https://community.openvpn.net/openvpn/wiki/OpenVPN3Linux>.

- 打开一个新的 VPN 会话：

```bash
openvpn3 session-start --config 路径/到/config.conf
```

- 列出已建立的会话：

```bash
openvpn3 sessions-list
```

- 断开当前建立的以给定配置开始的会话：

```bash
openvpn3 session-manage --config 路径/到/config.conf --disconnect
```

- 导入 VPN 配置：

```bash
openvpn3 config-import --config 路径/到/config.conf
```

- 列出导入的配置：

```bash
openvpn3 configs-list
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Nata Jam](mailto:71621144+wandersofb@users.noreply.github.com) | openvpn3: add Chinese translation (#7788) | 2022-02-17T14:17:44 | [8e149127b061](https://github.com/tldr-pages/tldr/commit/8e149127b061defe7a815b7534da96f31f125547)

