---
author: ['Minghao Liu']
date: 1659299157
title: "go clean"
description: "go clean, 移除目标文件和缓存文件。"
categories: "common"
---
> 更多信息：<https://golang.org/cmd/go/#hdr-Remove_object_files_and_cached_files>.

- 只打印移除命令，而不会真正移除任何东西：

```bash
go clean -n
```

- 删除编译缓存：

```bash
go clean -cache
```

- 删除所有测试结果缓存：

```bash
go clean -testcache
```

- 删除模块缓存：

```bash
go clean -modcache
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | go-*: add Chinese translation (#8266) | 2022-07-31T22:25:57 | [b15ee904f7f9](https://github.com/tldr-pages/tldr/commit/b15ee904f7f9939ce0b460fa2d30962540799fec)

