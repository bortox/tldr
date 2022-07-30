---
author: ['bl-ue', 'zhouquan', 'marchersimon']
date: 1630394029
title: "androguard"
description: "androguard, 使用 python 编写的一款针对安卓应用的逆向工程工具。"
categories: "common"
---
> 更多信息：<https://github.com/androguard/androguard>.

- 展示 Android manifest 清单文件：

```bash
androguard axml 路径/至/应用.apk
```

- 展示 app 元数据（版本和 app ID）：

```bash
androguard apkid 路径/至/应用.apk
```

- 反编译 Java 代码：

```bash
androguard decompile 路径/至/应用.apk --output 路径/至/目录
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

