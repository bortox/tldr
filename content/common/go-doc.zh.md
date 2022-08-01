---
author: ['Minghao Liu']
date: 1659299157
title: "go doc"
description: "go doc, 显示包或符号的文档。"
categories: "common"
---
> 更多信息：<https://golang.org/cmd/go/#hdr-Show_documentation_for_package_or_symbol>.

- 显示当前包的文档：

```bash
go doc
```

- 显示包文档及导出符号：

```bash
go doc encoding/json
```

- 同时显示符号的文档：

```bash
go doc -all encoding/json
```

- 同时显示源代码：

```bash
go doc -all -src encoding/json
```

- 显示指定的符号：

```bash
go doc -all -src encoding/json.Number
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Minghao Liu](mailto:HugueLiu@users.noreply.github.com) | go-*: add Chinese translation (#8266) | 2022-07-31T22:25:57 | [b15ee904f7f9](https://github.com/tldr-pages/tldr/commit/b15ee904f7f9939ce0b460fa2d30962540799fec)

