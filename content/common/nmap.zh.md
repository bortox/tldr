---
author: ['bl-ue', 'BillLucky', 'marchersimon']
date: 1633112881
title: "nmap"
description: "nmap, 网络探索工具和安全/端口扫描程序。"
categories: "common"
---
> 仅当以特权运行 Nmap 时，某些功能才激活。

> 更多信息：<https://nmap.org>.

- 检查 IP 地址是否可用，并猜测远程主机的操作系统：

```bash
nmap -O IP 或者 主机名
```

- 尝试确定指定的主机是否启动以及它们的名称是什么：

```bash
nmap -sn IP 或者 主机名 可选的其它地址
```

- 像上面一样，如果主机启动了，还可以运行默认的 1000 端口 TCP 扫描：

```bash
nmap IP 或者 主机名 可选的其它地址
```

- 也可以启用脚本，服务检测，操作系统指纹识别和跟踪路由：

```bash
nmap -A 一个地址 或者 多个地址
```

- 假设网络连接良好并加快执行速度：

```bash
nmap -T4 一个地址 或者 多个地址
```

- 扫描端口的特定列表（使用 `-p` 参数覆盖所有端口，如 `-p 1-65535`，也可以明确指定几个端口，如 `-p 3306,3307,3308`）：

```bash
nmap -p 端口1, 端口2, ..., 端口N 一个地址 或者 多个地址
```

- 执行 TCP 和 UDP 扫描（`-sU` 只用 UDP 扫描，`-sZ` 用 SCTP 扫描，`-sO` 用于 IP 扫描）：

```bash
nmap -sSU 一个地址 或者 多个地址
```

- 使用默认 NSE 脚本执行针对该主机地址的完整端口、服务、版本检测扫描，以确定弱点和信息：

```bash
nmap -sC -sV 一个地址 或者 多个地址
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | nmap: put command flags in example descriptions in backticks (#5812) | 2021-04-22T22:06:36 | [43901df7ecde](https://github.com/tldr-pages/tldr/commit/43901df7ecde69084a69fc82df6c77a314ab53b9)
[BillLucky](mailto:bill.libiao@gmail.com) | nmap: add Chinese translation (#5796) | 2021-04-22T15:38:58 | [0bbf60f290a7](https://github.com/tldr-pages/tldr/commit/0bbf60f290a78be929f23b1ad580be7ed1934dbd)

