---
author: ['gkah']
date: 1631104326
title: "arp-scan"
description: "arp-scan, 发送 ARP 数据包到特定主机（指定 IP 地址或主机名），来扫描本地网络。"
categories: "common"
---
> 更多信息：<https://github.com/royhills/arp-scan>.

- 扫描当前本地网络：

```bash
arp-scan --localnet
```

- 扫描带有自定义位掩码的 IP 网络：

```bash
arp-scan 192.168.1.1/24
```

- 扫描自定义范围内的 IP 网络：

```bash
arp-scan 127.0.0.0-127.0.0.31
```

- 扫描带有自定义子网掩码的 IP 网络：

```bash
arp-scan 10.0.0.0:255.255.255.0
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[gkah](mailto:47049232+Fivro@users.noreply.github.com) | arp-scan: move to common platform (#6395) | 2021-09-08T14:32:06 | [ef69c60c84c8](https://github.com/tldr-pages/tldr/commit/ef69c60c84c83ade68917e65c83476ab6c01ac9d)

