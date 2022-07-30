---
author: ['千玄子', 'bl-ue', 'marchersimon']
date: 1630394029
title: "avahi-browse"
description: "avahi-browse, 显示通过 mDNS/DNS-SD 暴露在本地网络的服务和主机。"
categories: "linux"
---
> Avahi 与苹果设备的 Bonjour（Zeroconf）兼容。

> 更多信息：<https://www.avahi.org/>.

- 列出本地网络中的所有服务和他们的地址与端口，忽略他们本地的地址和端口：

```bash
avahi-browse --all --resolve --ignore-local
```

- 列出所有的域名：

```bash
avahi-browse --browse-domains
```

- 只搜索一个特定的域名：

```bash
avahi-browse --all --domain=domain
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

