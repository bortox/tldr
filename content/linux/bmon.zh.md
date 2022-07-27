---
author: ['千玄子']
date: 1630035519
title: "bmon, TLDR Pages"
description: "bmon, 监控带宽并捕获网络相关统计信息。"
categories: "linux"
---
> 更多信息：<https://github.com/tgraf/bmon>.

- 显示所有接口的列表：

```bash
bmon -a
```

- 以每秒位数显示数据传输速率：

```bash
bmon -b
```

- 设置策略以定义显示哪些网络接口：

```bash
bmon -p interface_1,interface_2,interface_3
```

- 设置计算每个计数器速率的间隔（以秒为单位）：

```bash
bmon -R 2.0
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

