---
author: ['marchersimon', 'lincc']
date: 1643487459
title: "pdfgrep, TLDR Pages"
description: "pdfgrep, 在 PDF 文件中搜索文本。"
categories: "common"
---
> 更多信息：<https://pdfgrep.org>.

- 在 PDF 中查找与关键词匹配的行：

```bash
pdfgrep 关键词 文件.pdf
```

- 包含每个匹配行的文件名和页码：

```bash
pdfgrep --with-filename --page-number 关键词 文件.pdf
```

- 对以 "foo" 开头关键词搜索，返回前 3 个匹配项，不区分大小写：

```bash
pdfgrep --max-count 3 --ignore-case '^foo' 文件.pdf
```

- 在当前目录中扩展名为.pdf 的文件中递归查找关键词：

```bash
pdfgrep --recursive 关键词
```

- 在与当前目录中特定文件名 "*book.pdf" 匹配的文件上递归查找关键词：

```bash
pdfgrep --recursive --include '*book.pdf' 关键词
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

