---
author: ['LiLittleCat']
date: 1662000361
title: "df"
description: "df, 提供文件系统磁盘空间使用情况的概览。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/df>.

- 显示所有文件系统和它们的磁盘使用情况：

```bash
df
```

- 以人类可读的形式显示所有文件系统和它们的磁盘使用情况：

```bash
df -h
```

- 显示包含给定文件或目录的文件系统及其磁盘使用情况：

```bash
df 路径/到/文件或目录
```

- 显示索引节点数量的统计数据：

```bash
df -i
```

- 显示不包括指定类型的文件系统及其磁盘使用情况：

```bash
df -x squashfs -x tmpfs
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[LiLittleCat](mailto:luoyukongchan@outlook.com) | df: add Chinese translation (#8428) * df: add Chinese translation * Update pages.zh/common/df.md Co-authored-by: K.B.Dharun Krishna [...] | 2022-09-01T04:46:01 | [5290b205186a](https://github.com/tldr-pages/tldr/commit/5290b205186a9636eab63bce39d594041e9bb24e)

