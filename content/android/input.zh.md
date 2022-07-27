---
author: ['BillLucky', 'bl-ue', 'marchersimon']
date: 1633112881
title: "input, TLDR Pages"
description: "input, 将事件代码或触摸屏手势发送到 Android 设备。"
categories: "android"
---
> 此命令只能通过 `adb shell` 使用。

> 更多信息：<https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- 将单个字符的事件代码发送到 Android 设备：

```bash
input keyevent event_code
```

- 将文本发送到 Android 设备（`%s` 代表空格）：

```bash
input text "text"
```

- 将轻触发送到 Android 设备：

```bash
input tap x_pos y_pos
```

- 将滑动手势发送到 Android 设备：

```bash
input swipe x_start y_start x_end y_end duration_in_ms
```

- 使用滑动手势将长按发送到 Android 设备：

```bash
input swipe x_pos y_pos x_pos y_pos duration_in_ms
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | input: add Chinese translation (#6026) | 2021-05-23T16:50:09 | [242ac9ec04de](https://github.com/tldr-pages/tldr/commit/242ac9ec04de0cadfb8213a9ab3b0b1b69cb7aa8)

