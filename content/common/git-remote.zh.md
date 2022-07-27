---
author: ['Asurada']
date: 1637411259
title: "git remote, TLDR Pages"
description: "git remote, 管理跟踪的远程仓库（remotes）。"
categories: "common"
---
> 更多信息：<https://git-scm.com/docs/git-remote>.

- 列出已经存在的远程仓库，包括它们的名字和 URL：

```bash
git remote -v
```

- 查看某个远程仓库的信息：

```bash
git remote show 远程仓库名字
```

- 添加远程仓库：

```bash
git remote add 远程仓库名字 远程仓库 URL
```

- 更改远程仓库地址链接（使用 `--add` 选项不会移除现有的 URL）：

```bash
git remote set-url 远程仓库名字 新 URL
```

- 移除远程仓库：

```bash
git remote remove 远程仓库名字
```

- 重命名远程仓库：

```bash
git remote rename 旧名字 新名字
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Asurada](mailto:43401755+ousugo@users.noreply.github.com) | git-remote: add Chinese translation (#7459) | 2021-11-20T13:27:39 | [6ccf43e391dc](https://github.com/tldr-pages/tldr/commit/6ccf43e391dcfa58607dc0631e76535c22f19a9c)

