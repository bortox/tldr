---
author: ['千玄子']
date: 1630035519
title: "blkdiscard"
description: "blkdiscard, 丢弃存储设备上的设备扇区。对 SSD 有用。"
categories: "linux"
---
> 更多信息：<https://manned.org/blkdiscard>.

- 丢弃设备上的所有扇区，删除所有数据：

```bash
blkdiscard /dev/设备名
```

- 安全地丢弃设备上的所有块，删除所有数据：

```bash
blkdiscard --secure /dev/设备名
```

- 丢弃设备的前 100 MB：

```bash
blkdiscard --length 100MB /dev/设备名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

