---
author: ['lincc']
date: 1631128061
title: "cmd"
description: "cmd, Android 服務管理器。"
categories: "android"
---
> 更多資訊：<https://cs.android.com/android/platform/superproject/+/master:frameworks/native/cmds/cmd/>.

- 列出所有正在執行的服務：

```bash
cmd -l
```

- 呼叫指定服務：

```bash
cmd alarm
```

- 呼叫服務同時傳遞參數：

```bash
cmd vibrator vibrate 300
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

