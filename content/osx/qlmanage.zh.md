---
author: ['wizarot', 'Marco Bonelli', 'bl-ue', 'Ein Verne']
date: 1627893669
title: "qlmanage, TLDR Pages"
description: "qlmanage, QuickLook 服务器工具。"
categories: "osx"
---
- 快速显示一个或多个文件：

```bash
qlmanage -p 文件名 文件名 2
```

- 计算生成当前目录中所有 jpeg 文件的缩略图，300px 宽 png 格式，并将它们放在一个指定目录中：

```bash
qlmanage *.jpg -t -s 300 指定目录
```

- 重置快速查看：

```bash
qlmanage -r
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | qlmangle: fix typo (#3225) | 2019-08-06T13:08:09 | [50fe3706684f](https://github.com/tldr-pages/tldr/commit/50fe3706684faeacd9f1a7167ebadf7600add556)
[wizarot](mailto:wizarot@qq.com) | qlmanage: add Chinese translation | 2019-03-15T12:47:29 | [af362fc1516f](https://github.com/tldr-pages/tldr/commit/af362fc1516f4f6fe20c81e2bcc49c05c8827402)

