---
author: ['wizarot', 'meowmeowcat', 'Ein Verne', 'bl-ue']
date: 1635959386
title: "mkfile, TLDR Pages"
description: "mkfile, 创建一个或多个任意大小的空文件。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/mkfile.html>.

- 创建一个 15 千字节的空文件：

```bash
mkfile -n 15k 文件名
```

- 创建给定大小和单位的文件（bytes, KB, MB, GB）：

```bash
mkfile -n 大小b|k|m|g 文件名
```

- 创建两个 4 兆字节的文件：

```bash
mkfile -n 4m 文件名 1 文件名 2
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/m*: add more information link (#7371) | 2021-11-03T18:09:46 | [1e75baed72db](https://github.com/tldr-pages/tldr/commit/1e75baed72db8bc67f7edfc001cd572f755beba5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | mkfile: add Chinses translation | 2019-03-05T09:15:04 | [8f060518b613](https://github.com/tldr-pages/tldr/commit/8f060518b613bdc400f4c01447154b22bfedd501)

