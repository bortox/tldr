---
author: ['baiyutang']
date: 1646654797
title: "kitex, TLDR Pages"
description: "kitex, Code generation tool provided by the Go RPC framework Kitex."
categories: "common"
---
> Kitex accepts both thrift and protobuf IDLs, and supports generating a skeleton of a server side project.

> More information: <https://www.cloudwego.io>.

- Generate client codes when a project is in `$GOPATH`:

```bash
kitex path/to/IDL_file.thrift
```

- Generate client codes when a project is not in `$GOPATH`:

```bash
 kitex -module github.com/xx-org/xx-name path/to/IDL_file.thrift
```

- Generate client codes with protobuf IDL:

```bash
kitex -type protobuf path/to/IDL_file.proto
```

- Generate server codes:

```bash
kitex -service svc_name path/to/IDL_file.thrift
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[baiyutang](mailto:irichardwang@gmail.com) | kitex: add page (#7782) | 2022-03-07T13:06:37 | [5892e647dee3](https://github.com/tldr-pages/tldr/commit/5892e647dee34a0a7f85a56567fb2c76374bb701)

