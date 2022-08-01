---
author: ['Minghao Liu']
date: 1659299157
title: "go build"
description: "go build, 编译 Go 源代码。"
categories: "common"
---
> 更多信息：<https://golang.org/cmd/go/#hdr-Compile_packages_and_dependencies>.

- 编译‘package main’文件（输出为不带扩展名的文件名）：

```bash
go build 路径/到/main.go
```

- 编译，并指定输出文件名：

```bash
go build -o 路径/到/二进制文件 路径/到/源文件.go
```

- 编译一个包：

```bash
go build -o 路径/到/二进制文件 路径/到/包
```

- 编译 main 包为可执行文件，并开启数据竞态检测：

```bash
go build -race -o 路径/到/可执行文件 路径/到/main/包
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | go-*: add Chinese translation (#8266) | 2022-07-31T22:25:57 | [b15ee904f7f9](https://github.com/tldr-pages/tldr/commit/b15ee904f7f9939ce0b460fa2d30962540799fec)

