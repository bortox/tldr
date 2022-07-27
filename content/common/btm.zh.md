---
author: ['zhouquan', 'bl-ue', 'marchersimon']
date: 1630394029
title: "btm, TLDR Pages"
description: "btm, 命令行`top`的替代品。"
categories: "common"
---
> 比 `top` 更轻便，支持跨平台、图表更丰富。

> 更多信息：<https://github.com/ClementTsang/bottom>.

- 展示默认布局（cpu, 内存，温度，磁盘，网络和 进程）：

```bash
btm
```

- 开启基础模式，关闭图表和高亮（接近于 `top`）：

```bash
btm --basic
```

- 将图表中的小点换成大点：

```bash
btm --dot_marker
```

- 展示电池充电和健康状态：

```bash
btm --battery
```

- 设置图表刷新间隔和留存数据的时长：

```bash
btm --rate 250 --default_time_value 30000
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

