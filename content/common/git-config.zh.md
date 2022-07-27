---
author: ['Asurada']
date: 1637651703
title: "git config, TLDR Pages"
description: "git config, 管理 Git 仓库的自定义设置项。"
categories: "common"
---
> 这些设置可以分为局部设置（只对当前仓库生效）和全局设置（对当前用户生效）。

> 更多信息：<https://git-scm.com/docs/git-config>.

- 列出局部设置项（存储在当前仓库的 `.git/config`）：

```bash
git config --list --local
```

- 列出全局配置项（存储在 `~/.gitconfig`)：

```bash
git config --list --global
```

- 列出所有被修改过的配置项，包含局部的以及全局的：

```bash
git config --list
```

- 获取某个配置项的值：

```bash
git config alias.unstage
```

- 设置某个全局配置项：

```bash
git config --global alias.unstage "reset HEAD --"
```

- 将某个全局配置项恢复为默认值：

```bash
git config --global --unset alias.unstage
```

- 使用默认编辑器修改本地设置：

```bash
git config --edit
```

- 使用默认编辑器修改全局设置：

```bash
git config --global --edit
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Asurada](mailto:43401755+ousugo@users.noreply.github.com) | git-config: add Chinese translation (#7464) | 2021-11-23T08:15:03 | [e8c41c1e42a9](https://github.com/tldr-pages/tldr/commit/e8c41c1e42a977d20a94033656ad99ff7f249f77)

