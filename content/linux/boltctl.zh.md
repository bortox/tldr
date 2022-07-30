---
author: ['bl-ue', 'noarchwastaken', 'marchersimon']
date: 1630394029
title: "boltctl"
description: "boltctl, 控制雷电（thunderbolt）设备。"
categories: "linux"
---
> 更多信息：<https://manned.org/boltctl>.

- 列出已连接并授权的设备：

```bash
boltctl
```

- 列出已连接的设备，且包含未授权的设备：

```bash
boltctl list
```

- 临时授权一个设备：

```bash
boltctl authorize 设备uuid
```

- 授权并记住一个设备：

```bash
boltctl enroll 设备uuid
```

- 取消一个设备的授权：

```bash
boltctl forget 设备uuid
```

- 显示一个设备的详细信息：

```bash
boltctl info 设备uuid
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[noarchwastaken](mailto:noarch@n0ar.ch) | boltctl: add page (#5786) | 2021-05-13T04:15:30 | [c1259f5d7b61](https://github.com/tldr-pages/tldr/commit/c1259f5d7b61191e72304efc5ec3409fb873021f)

