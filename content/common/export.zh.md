---
author: ['marchersimon']
date: 1631539482
title: "export"
description: "export, 命令为当前 shell 中的子进程进行环境变量设置。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/bash/manual/bash.html#index-export>.

- 设置为新的环境变量：

```bash
export 某变量名=值
```

- 删除环境变量：

```bash
export -n 某变量名
```

- 给 PATH 追加新的路径进去：

```bash
export PATH=$PATH:追加的 path 路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)

