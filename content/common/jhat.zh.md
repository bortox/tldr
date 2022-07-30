---
author: ['BillLucky']
date: 1628238319
title: "jhat"
description: "jhat, Java 堆分析工具。"
categories: "common"
---
> 更多信息：<https://docs.oracle.com/javase/8/docs/technotes/tools/unix/jhat.html>.

- 分析堆转储文件（来自 jmap），通过 http 端口 7000 进行查看：

```bash
jhat 路径/堆转储文件
```

- 分析堆转储文件，为 http 服务指定备用端口：

```bash
jhat -p 端口 路径/堆转储文件
```

- 通过 jhat 分析转储文件，指定使用 8GB RAM（建议使用 2-4 倍的转储大小）：

```bash
jhat -J-mx8G 路径/堆转储文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[BillLucky](mailto:bill.libiao@gmail.com) | jhat: add Chinese translation (#6265) | 2021-08-06T10:25:19 | [e61ac03ef16e](https://github.com/tldr-pages/tldr/commit/e61ac03ef16e418b19dc29da66fabb4ccad26c6f)

