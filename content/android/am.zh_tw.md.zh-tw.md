---
author: ['Seth Falco', 'lincc']
date: 1648358715
title: "am, TLDR Pages"
description: "am, Android 活動管理器。"
categories: "android"
---
> 更多資訊：<https://developer.android.com/studio/command-line/adb#am>.

- 啟動一個指定的活動：

```bash
am start -n com.android.settings/.Settings
```

- 啟動一個活動並將資料傳遞給它：

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- 啟動與特定操作和類別匹配的活動：

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- 將意圖（intent）轉換為 URI：

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | android/*: add traditional Chinese translations (#6418) | 2021-09-08T21:07:41 | [cd0da6c11353](https://github.com/tldr-pages/tldr/commit/cd0da6c1135366585c048471a469c037f0d77a06)

