---
author: ['Niklas', 'marchersimon', 'lincc']
date: 1643487459
title: "yank"
description: "yank, 从 stdin 读取输入并显示一个选择界面，该界面允许选择一个字段并将其复制到剪贴板。"
categories: "common"
---
> 更多信息：<https://manned.org/yank>.

- 使用默认分隔符（\f, \n, \r, \s, \t）：

```bash
sudo dmesg | yank
```

- 输入单行：

```bash
sudo dmesg | yank -l
```

- 使用特定分 `=` 隔符输入：

```bash
echo hello=world | yank -d =
```

- 只有与特定正则表达式匹配的内容才输入：

```bash
ps ux | yank -g "[0-9]+"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Niklas](mailto:derNiklaas@users.noreply.github.com) | yank, yaourt: add more information link (#7049) | 2021-10-26T04:26:19 | [bf5c13a00d3b](https://github.com/tldr-pages/tldr/commit/bf5c13a00d3b256646326a4d3bfd23fddc5dbed3)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | whereis, xar, yank: move to common (#6552) | 2021-09-19T02:59:20 | [e94e6af88289](https://github.com/tldr-pages/tldr/commit/e94e6af88289f26bf25c85b45971f240f56d8672)

