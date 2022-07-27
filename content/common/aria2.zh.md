---
author: ['Starccy', 'bl-ue', 'Ein Verne']
date: 1627893669
title: "aria2, TLDR Pages"
description: "aria2, 一个轻量级多协议和多源命令行下载工具。"
categories: "common"
---
> 支持 HTTP, HTTPS, FTP, SFTP, BitTorrent and Metalink.

> 主页： <https://aria2.github.io/>.

- 下载一个网络资源：

```bash
aria2c http://example.org/myLinux.iso
```

- 从多个源处下载一个资源：

```bash
aria2c http://mirror1.org/myLinux.iso http://mirror2.org/myLinux.iso
```

- 使用两个连接下载资源：

```bash
aria2c -x2 http://example.org/myLinux.iso
```

- 从 Metalink URI 中下载资源：

```bash
aria2c http://example.org/myLinux.metalink
```

- 从 BitTorrent URI 中下载资源：

```bash
aria2c http://example.org/myLinux.torrent
```

- 从 BitTorrent Magnet URI 中下载资源：

```bash
aria2c 'magnet:?xt=urn:btih:248D0A1CD08284299DE78D5C1ED359BB46717D8C'
```

- 从一个文件中下载资源：

```bash
aria2c -i uris.txt
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | aria2: add Chinese translation | 2019-04-17T21:44:55 | [321d7aabb686](https://github.com/tldr-pages/tldr/commit/321d7aabb6867deedc9d60a8b46bb9ec86814cc2)

