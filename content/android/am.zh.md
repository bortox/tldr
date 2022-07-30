---
author: ['bl-ue', 'BillLucky', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "am"
description: "am, Android 活动管理器。"
categories: "android"
---
> 更多信息：<https://developer.android.com/studio/command-line/adb#am>.

- 启动一个指定的活动：

```bash
am start -n com.android.settings/.Settings
```

- 启动一个活动并将数据传递给它：

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- 启动与特定操作和类别匹配的活动：

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- 将意图转换为 URI：

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | am: add Chinese translation (#6021) | 2021-05-23T16:49:42 | [0ba1bba4404d](https://github.com/tldr-pages/tldr/commit/0ba1bba4404d3d7fc744ee92aae81f1f719cb183)

