---
author: ['lincc']
date: 1631128061
title: "logcat, TLDR Pages"
description: "logcat, 轉存系統訊息日誌。"
categories: "android"
---
> 更多資訊：<https://developer.android.com/studio/command-line/logcat>.

- 顯示系統日誌：

```bash
logcat
```

- 將系統日誌寫入檔案：

```bash
logcat -f 文件路径
```

- 顯示與正規表示式匹配的列：

```bash
logcat --regex 正規表示式
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

