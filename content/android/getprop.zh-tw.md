---
author: ['lincc']
date: 1631128061
title: "getprop"
description: "getprop, 顯示關於 Android 系統屬性的資訊。"
categories: "android"
---
> 更多資訊：<https://manned.org/getprop>.

- 顯示關於 Android 系統屬性的資訊：

```bash
getprop
```

- 顯示關於指定屬性的資訊：

```bash
getprop 屬性
```

- 顯示 SDK API 級別：

```bash
getprop ro.build.version.sdk
```

- 顯示 Android 版本：

```bash
getprop ro.build.version.release
```

- 顯示 Android 裝置型號：

```bash
getprop ro.vendor.product.model
```

- 顯示 OEM 解鎖狀態：

```bash
getprop ro.oem_unlock_supported
```

- 顯示 Android WiFi 卡的 MAC 地址：

```bash
getprop ro.boot.wifimacaddr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

