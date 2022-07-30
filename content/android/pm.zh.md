---
author: ['bl-ue', 'BillLucky', 'marchersimon']
date: 1633112881
title: "pm"
description: "pm, 显示关于 Android 设备上的应用程序的信息。"
categories: "android"
---
> 更多信息：<https://developer.android.com/studio/command-line/adb#pm>.

- 打印所有已安装应用程序的列表：

```bash
pm list packages
```

- 打印所有已安装的系统应用程序的列表：

```bash
pm list packages -s
```

- 打印所有已安装的第三方应用程序的列表：

```bash
pm list packages -3
```

- 打印与指定关键字匹配的应用程序列表：

```bash
pm list packages 关键词
```

- 打印指定应用的 APK 的路径：

```bash
pm path 应用名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | pm: add Chinese translation (#6028) | 2021-05-25T18:43:36 | [5740bd061a74](https://github.com/tldr-pages/tldr/commit/5740bd061a742dd1e56dbd96017034be8413c2a8)

