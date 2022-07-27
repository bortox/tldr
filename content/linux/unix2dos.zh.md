---
author: ['xphade', 'Flex Zhong', 'bl-ue', 'marchersimon']
date: 1656619119
title: "unix2dos, TLDR Pages"
description: "unix2dos, 将 Unix 样式的行尾更改为 DOS 样式。"
categories: "linux"
---
> 用 CRLF 替换 LF.

> 更多信息：<https://waterlan.home.xs4all.nl/dos2unix.html>.

- 更改文件的行尾：

```bash
unix2dos 文件名
```

- 使用 DOS 样式的行尾创建副本：

```bash
unix2dos -n 文件名 新文件名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[xphade](mailto:18196286+xphade@users.noreply.github.com) | dos2unix, mac2unix, unix2dos, unix2mac: fix error in descriptions (#8082) | 2022-06-30T21:58:39 | [ba5ce3932331](https://github.com/tldr-pages/tldr/commit/ba5ce393233134279bd4386feac891af500edfe8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | dos2unix, mac2unix, unix2dos, unix2mac: add Chinese translations (#4168) | 2020-07-17T18:55:40 | [33ee5d40d1c7](https://github.com/tldr-pages/tldr/commit/33ee5d40d1c763f9d8779804c4d2375dc3dfc699)

