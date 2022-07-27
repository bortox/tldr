---
author: ['errorcode']
date: 1628875176
title: "hexdump, TLDR Pages"
description: "hexdump, 一个 ASCII，十进制，十六进制，八进制转换查看工具。"
categories: "linux"
---
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
[errorcode](mailto:errorcode7@qq.com) | cp, grub-install, grub-mkconfig, hexdump, readelf: add Chinese translation (#6278) | 2021-08-13T19:19:36 | [39b5be991a84](https://github.com/tldr-pages/tldr/commit/39b5be991a84323b8fa746ce688cf044240b9752)

