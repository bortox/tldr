---
author: ['Tiny', 'bl-ue', 'marchersimon']
date: 1630394029
title: "debootstrap, TLDR Pages"
description: "debootstrap, 创建一个基本的 `Debian` 系统。"
categories: "linux"
---
> 更多信息：<https://wiki.debian.org/Debootstrap>.

- 在 `debian-root` 目录中创建一个 `Debian` 稳定分支系统：

```bash
sudo debootstrap stable path/to/debian-root/ http://deb.debian.org/debian
```

- 使用本地镜像在 `focal-root` 目录中创建一个 `Ubuntu 20.04` 系统：

```bash
sudo debootstrap focal path/to/focal-root/ file:///path/to/mirror/
```

- 切换到可引导系统：

```bash
sudo chroot path/to/root
```

- 列出可用的版本：

```bash
ls /usr/share/debootstrap/scripts/
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Tiny](mailto:freelxs@gmail.com) | debootstrap: add Chinese translation (#5802) | 2021-04-25T03:48:21 | [06c71c6a70ac](https://github.com/tldr-pages/tldr/commit/06c71c6a70acde3c23bb8ade9e3d4b11508334b7)

