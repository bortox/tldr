---
author: ['BillLucky']
date: 1629903871
title: "jmap"
description: "jmap, Java 内存映射工具。"
categories: "common"
---
> 更多信息：<https://docs.oracle.com/javase/7/docs/technotes/tools/share/jmap.html>.

- 打印 Java 进程的共享对象映射（类似 pmap 的输出）：

```bash
jmap Java 进程号
```

- 打印堆摘要信息：

```bash
jmap -heap Java 进程号
```

- 按类型打印堆使用的直方图：

```bash
jmap -histo Java 进程号
```

- 将堆的内容转储到二进制文件中以使用 jhat 进行分析：

```bash
jmap -dump:format=b,file=导出文件名 Java 进程号
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[BillLucky](mailto:bill.libiao@gmail.com) | jmap: add Chinese translation (#6403) | 2021-08-25T17:04:31 | [01daaf25a368](https://github.com/tldr-pages/tldr/commit/01daaf25a36836d0327cc000ca409e88fa795646)

