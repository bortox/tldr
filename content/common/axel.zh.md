---
author: ['zhouquan', 'bl-ue', 'marchersimon']
date: 1630394029
title: "axel, TLDR Pages"
description: "axel, 一款下载加速器。"
categories: "common"
---
> 支持 HTTP、HTTPS 和 FTP.

> 更多信息：<https://github.com/axel-download-accelerator/axel>.

- 链接下载：

```bash
axel 超链接
```

- 链接下载，指定文件名：

```bash
axel 超链接 -o 文件名称
```

- 多连接数下载：

```bash
axel -n 连接数量 超链接
```

- 查询镜像：

```bash
axel -S 镜像数量 超链接
```

- 限制下载速度（字节 bite 每秒）：

```bash
axel -s 字节数 超链接
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

