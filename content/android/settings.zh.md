---
author: ['BillLucky', 'bl-ue', 'marchersimon']
date: 1633112881
title: "settings, TLDR Pages"
description: "settings, 获取关于 Android OS 的信息。"
categories: "android"
---
> 更多信息：<https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- 在 `全局` 命名空间中显示环境变量列表：

```bash
settings list global
```

- 获取指定环境变量的值：

```bash
settings get global airplane_mode_on
```

- 设置指定环境变量的值：

```bash
settings put system screen_brightness 42
```

- 删除指定环境变量：

```bash
settings delete secure screensaver_enabled
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | settings: add Chinese translation (#6029) | 2021-05-23T16:51:09 | [d3b96202e61c](https://github.com/tldr-pages/tldr/commit/d3b96202e61c5382d7c55d6506974d34438ee767)

