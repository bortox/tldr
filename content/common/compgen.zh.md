---
author: ['marchersimon']
date: 1631539482
title: "compgen"
description: "compgen, 用于在 bash 中自动完成的内置命令，按两次 tab 键即可调用该命令。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/bash/manual/bash.html#index-compgen>.

- 显示所有可以执行的命令：

```bash
compgen -c
```

- 列出所有别名：

```bash
compgen -a
```

- 列出所有可以运行的函数：

```bash
compgen -A function
```

- 列出所有 shell 的保留关键字：

```bash
compgen -k
```

- 查看以 'ls' 开头的所有可用命令和别名：

```bash
compgen -ac ls
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)

