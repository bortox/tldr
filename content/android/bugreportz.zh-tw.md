---
author: ['Rafael Julio', 'lincc']
date: 1634730630
title: "bugreportz, TLDR Pages"
description: "bugreportz, 生成一個壓縮的 Android 錯誤報告。"
categories: "android"
---
> 此命令只能透過 `adb shell` 使用。

> 更多資訊：<https://cs.android.com/android/platform/superproject/+/master:frameworks/native/cmds/bugreportz>.

- 生成一個完整的 Android 裝置壓縮錯誤報告：

```bash
bugreportz
```

- 顯示正在執行的 `bugreportz` 的作業進度：

```bash
bugreportz -p
```

- 顯示 `bugreportz` 的版本：

```bash
bugreportz -v
```

- 顯示幫助資訊：

```bash
bugreportz -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | bugreport, bugreportz, fastboot: use links to code search (#7074) | 2021-10-20T13:50:30 | [e48d44f376dd](https://github.com/tldr-pages/tldr/commit/e48d44f376dd7610f183ca3d490fe9adfcf3e518)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

