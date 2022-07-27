---
author: ['xBLACKICEx']
date: 1634105814
title: "wc, TLDR Pages"
description: "wc, 计数行、单词或字节。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/wc>.

- 计数文件中的行数：

```bash
wc -l 文件
```

- 计数文件中的单词数：

```bash
wc -w 文件
```

- 计数文件中的字符（字节）：

```bash
wc -c 文件
```

- 计数文件中的字符数（考虑所有多字节的字符）：

```bash
wc -m 文件
```

- 使用标准输入，按顺序计数行、单词和字符（字节）：

```bash
find . | wc
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[xBLACKICEx](mailto:xBLACKICEx@outlook.com) | wc: add Chinese translation (#6950) | 2021-10-13T08:16:54 | [5d6b2367aa6d](https://github.com/tldr-pages/tldr/commit/5d6b2367aa6dcfcb66bdb3bfba8f0015efe2d376)

