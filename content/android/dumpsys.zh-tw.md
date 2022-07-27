---
author: ['lincc']
date: 1631128061
title: "dumpsys, TLDR Pages"
description: "dumpsys, 提供關於 Android 系統服務的資訊。"
categories: "android"
---
> 此命令只能透過 `adb shell` 使用。

> 更多資訊：<https://developer.android.com/studio/command-line/dumpsys>.

- 獲取所有系統服務的診斷輸出：

```bash
dumpsys
```

- 獲取指定系統服務的診斷輸出：

```bash
dumpsys 服務
```

- 列出 `dumpsys` 可以提供的所有服務資訊：

```bash
dumpsys -l
```

- 列出服務的指定服務引數：

```bash
dumpsys 服務 -h
```

- 從診斷輸出中排除指定服務：

```bash
dumpsys --skip 服務
```

- 指定超時時間，以秒為單位（預設為 10 秒）：

```bash
dumpsys -t 秒數
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

