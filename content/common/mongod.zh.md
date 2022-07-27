---
author: ['BillLucky', 'bl-ue', 'marchersimon']
date: 1633112881
title: "mongod, TLDR Pages"
description: "mongod, MongoDB 数据库服务器。"
categories: "common"
---
> 更多信息：<https://docs.mongodb.com/manual/reference/program/mongod>.

- 指定配置文件：

```bash
mongod --config filename
```

- 指定要监听的端口：

```bash
mongod --port port
```

- 指定数据库分析级别，用于性能调优分析。 0 - 关闭，1 - 仅是记录慢速操作，2 - 全部：

```bash
mongod --profile 0|1|2
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | mongod: add Chinese translation (#6020) | 2021-05-23T16:51:54 | [847965b1b244](https://github.com/tldr-pages/tldr/commit/847965b1b2440d328bcc6a620d59d35dfd00b0e0)

