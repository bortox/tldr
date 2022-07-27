---
author: ['Tiny', 'bl-ue', 'marchersimon']
date: 1630394029
title: "debuild, TLDR Pages"
description: "debuild, 从源代码构建 `Debian` 软件包的工具。"
categories: "linux"
---
> 更多信息：<https://manpages.debian.org/debuild>.

- 在当前目录中生成软件包：

```bash
debuild
```

- 仅构建二进制包：

```bash
debuild -b
```

- 生成软件包后，不运行 `lintian`（检查常见打包错误）：

```bash
debuild --no-lintian
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Tiny](mailto:freelxs@gmail.com) | debuild: add Chinese translation (#5801) | 2021-04-24T15:14:36 | [521c8cd74873](https://github.com/tldr-pages/tldr/commit/521c8cd748736a1ef1da44e3650ff1e2dc30b333)

