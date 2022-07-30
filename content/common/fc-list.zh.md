---
author: ['marchersimon']
date: 1631539539
title: "fc-list"
description: "fc-list, 列出系统上安装的可用字体。"
categories: "common"
---
> 更多信息：<https://manned.org/fc-list>.

- 返回系统中已安装字体的列表：

```bash
fc-list
```

- 返回具有给定名称的已安装字体的列表：

```bash
fc-list | grep 'DejaVu Serif'
```

- 返回系统中已安装字体的数量：

```bash
fc-list | wc -l
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | fc*: move to common (#6510) | 2021-09-13T15:25:39 | [7786008d9e1d](https://github.com/tldr-pages/tldr/commit/7786008d9e1d2b3ffa31c3e95ac0127e42466190)

