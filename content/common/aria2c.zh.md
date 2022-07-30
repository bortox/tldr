---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "aria2c"
description: "aria2c, 快速下载工具。"
categories: "common"
---
> 支持 HTTP(S), FTP, SFTP, BitTorrent, and Metalink.

> 更多信息：<https://aria2.github.io>.

- 下载一个 URI 到文件：

```bash
aria2c url
```

- 从多个源处下载一个资源：

```bash
aria2c url_1 url_2
```

- 通过保存在一个文件中的 URL 列表来下载资源：

```bash
aria2c -i 文件名
```

- 使用多个连接下载资源：

```bash
aria2c -s 连接数量 url
```

- 通过带用户名密码验证的 FTP 协议下载资源：

```bash
aria2c --ftp-user=用户名 --ftp-passwd=密码 url
```

- 限制下载速度（bytes/s）：

```bash
aria2c --max-download-limit=速度 url
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | aria2c: add Chinese translation | 2019-04-17T21:44:55 | [652d3dd5c6d3](https://github.com/tldr-pages/tldr/commit/652d3dd5c6d3fdac1078d034898237d78bda266b)
[Starccy](mailto:452276725@qq.com) | aria2c: add Chinese translation | 2019-04-17T21:44:55 | [4e4a7d5d7c8e](https://github.com/tldr-pages/tldr/commit/4e4a7d5d7c8e809725baf1797cce19463650036c)
[Starccy](mailto:452276725@qq.com) | aria2c: add Chinese translation | 2019-04-17T21:44:55 | [424299fd878f](https://github.com/tldr-pages/tldr/commit/424299fd878f46366d610d5e7b27f634bf9cfc0c)

