---
author: ['BillLucky', 'bl-ue', 'marchersimon']
date: 1633112881
title: "jarsigner, TLDR Pages"
description: "jarsigner, 签名并验证 Java 存档（JAR）文件。"
categories: "common"
---
> 更多信息：<https://docs.oracle.com/javase/9/tools/jarsigner.htm>.

- 签名一个 `JAR` 文件：

```bash
jarsigner path/to/file.jar keystore_alias
```

- 使用特定算法对 `JAR` 文件进行签名：

```bash
jarsigner -sigalg algorithm path/to/file.jar keystore_alias
```

- 验证 `JAR` 文件的签名：

```bash
jarsigner -verify path/to/file.jar
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | jarsigner: add Chinese translation (#6005) | 2021-05-21T10:07:16 | [2df401d613e1](https://github.com/tldr-pages/tldr/commit/2df401d613e14f59633338d58e0ac3a1de06664a)

