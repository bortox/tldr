---
author: ['bl-ue', 'BillLucky', 'marchersimon']
date: 1633112881
title: "dumpsys"
description: "dumpsys, 提供关于 Android 系统服务的信息。"
categories: "android"
---
> 此命令只能通过 `adb shell` 使用。

> 更多信息：<https://developer.android.com/studio/command-line/dumpsys>.

- 获取所有系统服务的诊断输出：

```bash
dumpsys
```

- 获取指定系统服务的诊断输出：

```bash
dumpsys 服务
```

- 列出 `dumpsys` 可以提供的所有服务信息：

```bash
dumpsys -l
```

- 列出服务的指定服务参数：

```bash
dumpsys 服务 -h
```

- 从诊断输出中排除指定服务：

```bash
dumpsys --skip 服务
```

- 指定超时时间，以秒为单位（默认为 10s）：

```bash
dumpsys -t 秒数
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | dumpsys: add Chinese translation (#6024) | 2021-05-25T18:56:16 | [13836d2150d2](https://github.com/tldr-pages/tldr/commit/13836d2150d28d245eac1bd5a8e734d8c3644829)

