---
author: ['zhouquan', 'bl-ue', 'marchersimon']
date: 1630394029
title: "bmaptool, TLDR Pages"
description: "bmaptool, 便捷地创建或复制块文件映射（被设计的比`cp`或`dd`更快）。"
categories: "common"
---
> 更多信息：<https://source.tizen.org/documentation/reference/bmaptool>.

- 使用图片生成块图文件：

```bash
bmaptool create -o blockmap 格式文件.bmap 图片文件
```

- 复制图片到指定目录：

```bash
bmaptool copy --bmap blockmap 格式文件 图片文件 /开发路径/sdb
```

- 复制压缩后的图片到指定目录：

```bash
bmaptool copy --bmap blockmap 格式文件 图片文件.gz /开发路径/sdb
```

- 复制图片的时候，不将图片转成块图：

```bash
bmaptool copy --nobmap 图片文件 /开发路径/sdb
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

