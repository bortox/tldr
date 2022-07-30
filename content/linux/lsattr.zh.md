---
author: ['xiaolong']
date: 1629355531
title: "lsattr"
description: "lsattr, 列出 Linux 系统下的文件属性。"
categories: "linux"
---
> 更多信息：<https://manned.org/lsattr>.

- 显示当前目录下文件的属性：

```bash
lsattr
```

- 列出指定路径下的文件属性：

```bash
lsattr path
```

- 递归列出当前目录及其子目录中所有文件属性：

```bash
lsattr -R
```

- 显示当前目录下所有文件的属性，包括隐藏文件：

```bash
lsattr -a
```

- 显示当前目录下的目录属性：

```bash
lsattr -d
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[xiaolong](mailto:65013593+xiaolong-666@users.noreply.github.com) | add lsattr Chinese translation (#6386) | 2021-08-19T08:45:31 | [2b7a18fc18b4](https://github.com/tldr-pages/tldr/commit/2b7a18fc18b482946206c1e911e6036a9045f50a)

