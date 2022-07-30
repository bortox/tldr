---
author: ['Antyna']
date: 1630515129
title: "lvs"
description: "lvs, 显示逻辑卷信息。"
categories: "linux"
---
> 另见：`lvm`.

> 更多信息：<https://man7.org/linux/man-pages/man8/lvs.8.html>.

- 显示逻辑卷信息：

```bash
lvs
```

- 显示所有逻辑卷：

```bash
lvs -a
```

- 改变默认显示以显示更多细节：

```bash
lvs -v
```

- 只显示特定字段：

```bash
lvs -o 域名 1,域名 2
```

- 将字段附加到显示：

```bash
lvs -o +域名
```

- 抑制标题行：

```bash
lvs --noheadings
```

- 使用特殊分隔符分隔特定字段：

```bash
lvs --separator =
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Antyna](mailto:xiaozaihu@gmail.com) | lvs: add Chinese translation (#6443) | 2021-09-01T18:52:09 | [fb0412d03bf7](https://github.com/tldr-pages/tldr/commit/fb0412d03bf7300603a308266b2793a284a3fb78)

