---
author: ['bl-ue', 'zhouquan', 'marchersimon']
date: 1630394029
title: "browser-sync"
description: "browser-sync, 启动一个本地的服务，可以监听文件改动，刷新浏览器。"
categories: "common"
---
> 更多信息：<https://browsersync.io/docs/command-line>.

- 将指定目录发成服务：

```bash
browser-sync start --server 路径/到/目录 --files 路径/到/目录
```

- 启动当前目录服务，同时监听指定目录下 `css` 文件的变动：

```bash
browser-sync start --server --files '路径/到/目录/*.css'
```

- 创建配置文件：

```bash
browser-sync init
```

- 按指定配置文件中的配置启动服务：

```bash
browser-sync start --config 配置文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

