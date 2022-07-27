---
author: ['marchersimon', 'bl-ue', 'lincc']
date: 1643487459
title: "shasum, TLDR Pages"
description: "shasum, 计算或检查加密 SHA 校验值。"
categories: "common"
---
> 更多信息：<https://manned.org/shasum>.

- 计算文件的 SHA1 校验值：

```bash
shasum 文件名
```

- 计算文件的 SHA256 校验值：

```bash
shasum --algorithm 256 文件名
```

- 计算多个文件的 SHA512 校验值：

```bash
shasum --algorithm 512 文件名 1 文件名 2
```

- 计算一个文件内列出的所有的目录文件的相对应的总数：

```bash
shasum --check 列表文件
```

- 从标准输入中获取并计算 SHA1 校验值：

```bash
其他命令 | shasum
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | arch, bzip2, command, gunicorn, history, htop, shasum, stty, yes: move translation to correct directories (#5362) | 2021-03-07T21:50:02 | [9ffbe151a610](https://github.com/tldr-pages/tldr/commit/9ffbe151a610c34f28be6b04816bfe83e9145104)

