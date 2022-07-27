---
author: ['bl-ue', 'marchersimon']
date: 1633112881
title: "gunicorn, TLDR Pages"
description: "gunicorn, Python 的 WSGI http 服务器。"
categories: "common"
---
> 更多信息：<https://gunicorn.org/>.

- 运行 python web 应用程序：

```bash
gunicorn 导入路径：应用程序
```

- 在 localhost 上监听 8080 端口：

```bash
gunicorn --bind localhost:8080 导入路径：应用程序
```

- 启用实时自动加载：

```bash
gunicorn --reload 导入路径：应用程序
```

- 使用 4 个工作进程处理请求：

```bash
gunicorn --workers 4 导入路径：应用程序
```

- 使用 4 个工作线程处理请求：

```bash
gunicorn --threads 4 导入路径：应用程序
```

- 通过 https 运行应用程序：

```bash
gunicorn --certfile cert.pem --keyfile key.pem 导入路径：应用程序
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | arch, bzip2, command, gunicorn, history, htop, shasum, stty, yes: move translation to correct directories (#5362) | 2021-03-07T21:50:02 | [9ffbe151a610](https://github.com/tldr-pages/tldr/commit/9ffbe151a610c34f28be6b04816bfe83e9145104)

