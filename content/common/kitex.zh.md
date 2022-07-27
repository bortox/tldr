---
author: ['baiyutang']
date: 1646654797
title: "kitex, TLDR Pages"
description: "kitex, Kitex 是 Go RPC 框架 Kitex 框架提供的用于生成代码的一个命令行工具。"
categories: "common"
---
> 目前，kitex 支持 thrift 和 protobuf 的 IDL，并支持生成一个服务端项目的骨架。

> 更多信息：<https://www.cloudwego.io>.

- 生成客户端代码，项目在 `$GOPATH` 目录下：

```bash
kitex 路径/到/IDL文件.thrift
```

- 生成客户端代码，项目不在 `$GOPATH` 目录下：

```bash
 kitex -module github.com/xx-org/xx-name 路径/到/IDL文件.thrift
```

- 根据 protobuf IDL 文件生成客户端代码：

```bash
kitex -type protobuf 路径/到/IDL文件.proto
```

- 生成服务端代码：

```bash
kitex -service svc_name 路径/到/IDL文件.thrift
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[baiyutang](mailto:irichardwang@gmail.com) | kitex: add page (#7782) | 2022-03-07T13:06:37 | [5892e647dee3](https://github.com/tldr-pages/tldr/commit/5892e647dee34a0a7f85a56567fb2c76374bb701)

