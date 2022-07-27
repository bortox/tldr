---
author: ['Asurada']
date: 1637652215
title: "Get-FileHash, TLDR Pages"
description: "Get-FileHash, 计算一个文件的 HASH 值。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/powershell/module/microsoft.powershell.utility/get-filehash>.

- 使用 SHA256 算法计算给定文件的哈希值：

```bash
Get-FileHash 文件路径
```

- 使用指定的哈希算法计算给定文件的哈希值：

```bash
Get-FileHash 文件路径 -Algorithm SHA1|SHA384|SHA256|SHA512|MD5
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Asurada](mailto:43401755+ousugo@users.noreply.github.com) | get-filehash: add Chinese translation (#7463) | 2021-11-23T08:23:35 | [099551735ab1](https://github.com/tldr-pages/tldr/commit/099551735ab1db329e3358b94afa1b67e82b0ed8)

