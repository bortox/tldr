---
author: ['Nata Jam']
date: 1645381129
title: "go"
description: "go, 管理 Go 源代码的工具。"
categories: "common"
---
> 此命令也有关于其子命令的文件，例如：`go build`.

> 更多信息：<https://golang.org>.

- 下载并安装由其路径指定的包：

```bash
go get 路径/到/包
```

- 编译并运行一个源文件（它必须包含一个 `main` 包）：

```bash
go run 文件.go
```

- 将源文件编译为当前命名的可执行文件：

```bash
go build -o 可执行文件 文件.go
```

- 编译当前目录中的包：

```bash
go build
```

- 执行当前包中的所有测试用例（文件必须以 `_test.go` 结尾）：

```bash
go test
```

- 编译并安装当前包：

```bash
go install
```

- 在当前目录下初始化一个新模块：

```bash
go mod init 模块
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Nata Jam](mailto:71621144+wandersofb@users.noreply.github.com) | go: add Chinese translation (#7799) | 2022-02-20T19:18:49 | [c5bc16a46536](https://github.com/tldr-pages/tldr/commit/c5bc16a4653687b51c61c9e6a41aa313a01ac036)

