---
author: ['BillLucky', 'bl-ue', 'marchersimon']
date: 1633112881
title: "getprop, TLDR Pages"
description: "getprop, 显示关于 Android 系统属性的信息。"
categories: "android"
---
> 更多信息：<https://manned.org/getprop>.

- 显示关于 Android 系统属性的信息：

```bash
getprop
```

- 显示关于指定属性的信息：

```bash
getprop prop
```

- 显示 SDK API 级别：

```bash
getprop ro.build.version.sdk
```

- 显示 Android 版本：

```bash
getprop ro.build.version.release
```

- 显示 Android 设备型号：

```bash
getprop ro.vendor.product.model
```

- 显示 OEM 解锁状态：

```bash
getprop ro.oem_unlock_supported
```

- 显示 Android WiFi 卡的 MAC 地址：

```bash
getprop ro.boot.wifimacaddr
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | getprop: add Chinese translation (#6025) | 2021-05-23T16:50:02 | [fb3e719fad6a](https://github.com/tldr-pages/tldr/commit/fb3e719fad6a090f8b23c960eac2be4e6d86b803)

