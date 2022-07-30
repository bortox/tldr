---
author: ['marchersimon']
date: 1633112881
title: "tree"
description: "tree, 以树的形式显示当前目录的内容。"
categories: "common"
---
> 更多信息：<http://mama.indstate.edu/users/ice/tree/>.

- 显示深度达到 “级数” 级的文件和目录（其中 1 表示当前目录）：

```bash
tree -L 级数
```

- 只显示目录：

```bash
tree -d
```

- 同时显示隐藏文件：

```bash
tree -a
```

- 打印没有缩进行的树，显示完整路径（使用`-N`不转义空格和特殊字符）：

```bash
tree -i -f
```

- 以可读格式打印每个文件节点的大小，目录显示其累积大小（类似在`du`命令中所示）：

```bash
tree -s -h --du
```

- 使用通配符（glob）模式在树层次结构中查找文件，并删除不包含匹配文件的目录：

```bash
tree -P '*.txt' --prune
```

- 在树层次结构中查找目录，删除不属于所需目录的目录：

```bash
tree -P 文件夹名 --matchdirs --prune
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

