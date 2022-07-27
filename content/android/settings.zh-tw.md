---
author: ['lincc']
date: 1631128061
title: "settings, TLDR Pages"
description: "settings, 獲取關於 Android OS 的資訊。"
categories: "android"
---
> 更多資訊：<https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- 在 `global` 命名空間中顯示環境變數列表：

```bash
settings list global
```

- 獲取指定環境變數的值：

```bash
settings get global airplane_mode_on
```

- 設定指定環境變數的值：

```bash
settings put system screen_brightness 42
```

- 刪除指定環境變數：

```bash
settings delete secure screensaver_enabled
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

