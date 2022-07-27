---
author: ['lincc']
date: 1631128061
title: "pm, TLDR Pages"
description: "pm, 顯示關於 Android 裝置上的應用程式的資訊。"
categories: "android"
---
> 更多資訊：<https://developer.android.com/studio/command-line/adb#pm>.

- 印出所有已安裝應用程式的列表：

```bash
pm list packages
```

- 印出所有已安裝的系統應用程式的列表：

```bash
pm list packages -s
```

- 印出所有已安裝的第三方應用程式的列表：

```bash
pm list packages -3
```

- 印出與指定關鍵字匹配的應用程式列表：

```bash
pm list packages 關鍵詞
```

- 印出指定應用程式的 APK 的路徑：

```bash
pm path 應用名
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

