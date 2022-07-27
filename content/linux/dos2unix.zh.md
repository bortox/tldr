---
author: ['Stig124', 'xphade', 'Flex Zhong', 'bl-ue', 'marchersimon']
date: 1656619119
title: "dos2unix, TLDR Pages"
description: "dos2unix, 将 DOS 样式的行尾更改为 Unix 样式。"
categories: "linux"
---
> 用 LF 替换 CRLF.

> 更多信息：<https://manned.org/dos2unix>.

- 更改文件的行尾：

```bash
dos2unix 文件名
```

- 使用 Unix 样式的行尾创建副本：

```bash
dos2unix -n 文件名 文件名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[xphade](mailto:18196286+xphade@users.noreply.github.com) | dos2unix, mac2unix, unix2dos, unix2mac: fix error in descriptions (#8082) | 2022-06-30T21:58:39 | [ba5ce3932331](https://github.com/tldr-pages/tldr/commit/ba5ce393233134279bd4386feac891af500edfe8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Flex Zhong](mailto:chungzh07@gmail.com) | dos2unix, mac2unix, unix2dos, unix2mac: add Chinese translations (#4168) | 2020-07-17T18:55:40 | [33ee5d40d1c7](https://github.com/tldr-pages/tldr/commit/33ee5d40d1c763f9d8779804c4d2375dc3dfc699)

