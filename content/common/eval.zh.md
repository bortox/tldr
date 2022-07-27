---
author: ['Seth Falco', 'marchersimon']
date: 1648358715
title: "eval, TLDR Pages"
description: "eval, 在当前 shell 中以单个命令的形式执行参数，并返回其结果。"
categories: "common"
---
> 更多信息：<https://manned.org/eval>.

- 使用 'foo' 做为参数调用 `echo`：

```bash
eval "echo foo"
```

- 在当前 shell 程序中设置变量：

```bash
eval "foo=bar"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)

