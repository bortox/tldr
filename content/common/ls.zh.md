---
author: ['LiLittleCat']
date: 1660764663
title: "ls"
description: "ls, 列出目录中的内容。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/ls>.

- 列出目录中的文件，每个文件占一行：

```bash
ls -1
```

- 列出包含隐藏文件的所有文件：

```bash
ls -a
```

- 列出所有文件，如果是目录，则在目录名后面加上「/」：

```bash
ls -F
```

- 列出包含隐藏文件的所有文件信息，包括权限，所有者，大小和修改日期：

```bash
ls -la
```

- 列出所有文件信息，大小用人类可读的单位表示（KiB, MiB, GiB）：

```bash
ls -lh
```

- 列出所有文件信息，按大小降序排序：

```bash
ls -lS
```

- 列出所有文件信息，按修改日期从旧到新排序：

```bash
ls -ltr
```

- 只列出目录：

```bash
ls -d */
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[LiLittleCat](mailto:luoyukongchan@outlook.com) | ls: add Chinese translation (#8360) | 2022-08-17T21:31:03 | [bba7a6c7dabf](https://github.com/tldr-pages/tldr/commit/bba7a6c7dabf6ffaad374e3f60aa169549f74ee1)

