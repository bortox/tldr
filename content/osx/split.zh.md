---
author: ['wizarot', 'bl-ue', 'Ein Verne']
date: 1627893669
title: "split, TLDR Pages"
description: "split, 把一个文件拆分成几块。"
categories: "osx"
---
- 分割一个文件，每个分割部分有 10 行（除了最后一个）：

```bash
split -l 10 文件名
```

- 用正则表达式拆分文件。匹配行将是下一个输出文件的第一行：

```bash
split -p cat|^[dh]og 文件名
```

- 拆分一个文件，每个拆分中有 512 个字节（除了最后一个文件，使用 512K 表示 Kb，512M 表示 Mb）：

```bash
split -b 512 文件名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | split: add Chinese translation | 2019-03-15T12:47:29 | [76f161d31e32](https://github.com/tldr-pages/tldr/commit/76f161d31e32a06fad67612cda9e8cbfc04e6748)

