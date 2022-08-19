---
author: ['lincc', 'Guohan Li']
date: 1660872445
title: "brew"
description: "brew, Linux 和 macOS 的包管理器。"
categories: "common"
---
> 更多信息：<https://brew.sh>.

- 安装最新稳定版的配方（formula）或木桶（cask），使用 `--devel` 安装开发版：

```bash
brew install 配方
```

- 列出所有已安装的配方和木桶：

```bash
brew list
```

- 升级已安装的配方或木桶（如果没有指定，则升级所有已安装的配方/木桶）：

```bash
brew upgrade 配方
```

- 从 Homebrew 源存储库中获取最新版本的 Homebrew 以及所有配方和木桶：

```bash
brew update
```

- 显示有新版本的配方和木桶：

```bash
brew outdated
```

- 搜索可用的配方（即包）和木桶（即原生包）：

```bash
brew search 包名
```

- 显示有关配方或木桶的信息（版本、安装路径、依赖等）：

```bash
brew info 配方
```

- 检查本地 Homebrew 安装包是否有潜在问题：

```bash
brew doctor
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Guohan Li](mailto:44457621+guohanli@users.noreply.github.com) | brew: fix simplified Chinese translation (#8368) Some words are written in traditional Chinese, which should be simplified Chinese. | 2022-08-19T03:27:25 | [93ed1e48385c](https://github.com/tldr-pages/tldr/commit/93ed1e48385c458f3d823f192f5359c9812fcc37)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | brew: sync traditional Chinese translation (#6492) | 2021-09-08T16:51:00 | [d30ee43e7d48](https://github.com/tldr-pages/tldr/commit/d30ee43e7d48a803c5c3bc369b16e6ba628be9eb)

