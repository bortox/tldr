---
author: ['千玄子']
date: 1630035519
title: "blkid, TLDR Pages"
description: "blkid, 列出所有已识别的分区及其通用唯一标识符 (UUID)。"
categories: "linux"
---
> 更多信息：<https://manned.org/blkid>.

- 列出所有分区：

```bash
sudo blkid
```

- 列出表中的所有分区，包括当前挂载点：

```bash
sudo blkid -o list
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

