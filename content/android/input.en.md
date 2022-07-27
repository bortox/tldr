---
author: ['marchersimon']
date: 1619122161
title: "input, TLDR Pages"
description: "input, Send event codes or touchscreen gestures to an Android device."
categories: "android"
---
> This command can only be used through `adb shell`.

> More information: <https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- Send an event code for a single character to an Android device:

```bash
input keyevent event_code
```

- Send a text to an Android device (`%s` represents spaces):

```bash
input text "text"
```

- Send a single tap to an Android device:

```bash
input tap x_pos y_pos
```

- Send a swipe gesture to an Android device:

```bash
input swipe x_start y_start x_end y_end duration_in_ms
```

- Send a long press to an Android device using a swipe gesture:

```bash
input swipe x_pos y_pos x_pos y_pos duration_in_ms
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: fix command descriptions (#5807) | 2021-04-22T22:09:21 | [4b891616c6a1](https://github.com/tldr-pages/tldr/commit/4b891616c6a1f21e836b56d216b7ec008e1dd746)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | input: add page (#5740) | 2021-04-13T17:58:16 | [a048bdb1bf49](https://github.com/tldr-pages/tldr/commit/a048bdb1bf49a974c259901378c63140eb010721)

