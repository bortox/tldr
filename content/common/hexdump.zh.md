---
author: ['marchersimon']
date: 1631999108
title: "hexdump, TLDR Pages"
description: "hexdump, 一个 ASCII，十进制，十六进制，八进制转换查看工具。"
categories: "common"
---
> 更多信息：<https://manned.org/hexdump>.

- 打印文件的十六进制表示形式：

```bash
hexdump 文件
```

- 以十六进制显示输入偏移量，并在最后两列中显示其 ASCII 表示形式：

```bash
hexdump -C 文件
```

- 显示文件的十六进制表示，但只解释输入的 N 个字节：

```bash
hexdump -C -n字节数 文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | hexdump, logger, netstat, n, nm, pdfgrep: move to common (#6549) | 2021-09-18T23:05:08 | [442a013cb866](https://github.com/tldr-pages/tldr/commit/442a013cb86602dfb50e4beb8bd2f66dc97e117d)

