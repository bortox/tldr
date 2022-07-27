---
author: ['Axel Navarro']
date: 1637774603
title: "git switch, TLDR Pages"
description: "git switch, 切换 Git 分支。要求 Git 版本在 2.23 以上。"
categories: "common"
---
> 另请参阅 `git checkout`。

> 更多信息：<https://git-scm.com/docs/git-switch>.

- 切换到一个已有的分支：

```bash
git switch 分支名字
```

- 创建并切换到一个新分支：

```bash
git switch --create 分支名字
```

- 创建并切换到基于某个提交的新分支：

```bash
git switch --create 分支名字 指定提交
```

- 切换到之前的分支：

```bash
git switch -
```

- 切换到一个分支，并更新所有匹配的子模块：

```bash
git switch --recurse-submodules 分支名字
```

- 切换到一个分支，并和当前分支以及暂未提交的修改进行三方合并：

```bash
git switch --merge 分支名字
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-switch: fix container folder (#7476) | 2021-11-24T18:23:23 | [ebaecf276544](https://github.com/tldr-pages/tldr/commit/ebaecf27654411d817769583c4b7ea8ee2330cf9)

