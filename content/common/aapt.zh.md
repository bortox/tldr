---
author: ['bl-ue', 'zhouquan', 'marchersimon']
date: 1633112881
title: "aapt"
description: "aapt, 安卓资源包工具（Android Asset Packaging Tools）。"
categories: "common"
---
> 该工具可以查看，创建，更新资源压缩包（zip, jar, apk）。

> 更多信息：<https://elinux.org/Android_aapt>.

- 列出资源压缩包里的内容：

```bash
aapt list 路径/到/应用.apk
```

- 查看 APK 包内指定的内容（版本，权限许可等）：

```bash
aapt dump badging 路径/到/应用.apk
```

- 打包生成资源压缩包：

```bash
aapt package -F 路径/到/应用.apk 路径/到/目录
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

