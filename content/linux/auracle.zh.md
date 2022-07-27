---
author: ['千玄子', 'bl-ue', 'marchersimon']
date: 1630394029
title: "auracle, TLDR Pages"
description: "auracle, 用来和 Arch Linux 用户仓库交互的命令行工具，这个仓库通常被称作 AUR."
categories: "linux"
---
> 更多信息：<https://github.com/falconindy/auracle>.

- 显示符合一个正则表达式的 AUR 包：

```bash
auracle search 'regular_expression'
```

- 显示 AUR 包列表的包信息，包名以一个单独的空格分隔：

```bash
auracle info package1 package2
```

- 显示 AUR 包列表的 `PKGBUILD` 文件（编译信息），包名以一个单独的空格分隔：

```bash
auracle show package1 package2
```

- 显示已安装 AUR 包的更新：

```bash
auracle outdated
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

