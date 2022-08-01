---
author: ['Minghao Liu']
date: 1659299157
title: "go env"
description: "go env, 管理 Go 工具链使用的环境变量。"
categories: "common"
---
> 更多信息：<https://golang.org/cmd/go/#hdr-Print_Go_environment_information>.

- 显示所有环境变量：

```bash
go env
```

- 显示指定的环境变量：

```bash
go env GOPATH
```

- 设置某个环境变量为指定值：

```bash
go env -w GOBIN=路径/到/目录
```

- 重置某个环境变量的值：

```bash
go env -u GOBIN
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | go-*: add Chinese translation (#8266) | 2022-07-31T22:25:57 | [b15ee904f7f9](https://github.com/tldr-pages/tldr/commit/b15ee904f7f9939ce0b460fa2d30962540799fec)

