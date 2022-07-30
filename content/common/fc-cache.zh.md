---
author: ['marchersimon']
date: 1631539539
title: "fc-cache"
description: "fc-cache, 扫描字体目录，以便建立字体缓存文件。"
categories: "common"
---
> 更多信息：<https://manned.org/fc-cache>.

- 生成字体缓存文件：

```bash
fc-cache
```

- 强制重建所有字体缓存文件，而不检查缓存是否为最新版本：

```bash
fc-cache -f
```

- 删除字体缓存文件，然后生成新的字体缓存文件：

```bash
fc-cache -r
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | fc*: move to common (#6510) | 2021-09-13T15:25:39 | [7786008d9e1d](https://github.com/tldr-pages/tldr/commit/7786008d9e1d2b3ffa31c3e95ac0127e42466190)

