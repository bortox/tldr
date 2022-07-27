---
author: ['wizarot', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "defaults, TLDR Pages"
description: "defaults, 读取和写入 macOS 应用程序的用户配置。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/defaults.html>.

- 读取应用程序选项的系统默认值：

```bash
defaults read 应用名 选项
```

- 读取应用程序选项的默认值：

```bash
defaults read -app 应用名 选项
```

- 写入应用程序选项的默认值：

```bash
defaults write 应用名 选项 - 类型 值
```

- 加速任务控制界面弹出动画（时间设置为 0.1）：

```bash
defaults write com.apple.Dock expose-animation-duration -float 0.1
```

- 删除应用程序的所有默认值：

```bash
defaults delete 应用名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | defaults: add Chinese translation | 2019-02-26T19:50:35 | [600af0ce3327](https://github.com/tldr-pages/tldr/commit/600af0ce3327ce74a6bc252a4de4c2bac27b7db3)

