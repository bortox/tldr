---
author: ['lincc']
date: 1631112660
title: "brew"
description: "brew, Linux 和 macOS 的套件管理工具。"
categories: "common"
---
> 更多資訊：<https://brew.sh>.

- 安裝最新穩定版的配方（formula）或木桶（cask），使用 `--devel` 安裝開發版：

```bash
brew install 配方
```

- 列出所有已安裝的配方和木桶：

```bash
brew list
```

- 更新已安裝的配方或木桶（如果沒有指定，則更新所有已安裝的配方/木桶）：

```bash
brew upgrade 配方
```

- 從 Homebrew 源倉庫中獲取最新版本的 Homebrew 以及所有配方和木桶：

```bash
brew update
```

- 顯示有新版本的配方和木桶：

```bash
brew outdated
```

- 搜尋可用的配方（即套件）和木桶（即原生套件）：

```bash
brew search 套件名
```

- 顯示有關配方或木桶的資訊（版本、安裝路徑、相依套件等）：

```bash
brew info 配方
```

- 檢查本機 Homebrew 套件是否有潛在問題：

```bash
brew doctor
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | brew: sync traditional Chinese translation (#6492) | 2021-09-08T16:51:00 | [d30ee43e7d48](https://github.com/tldr-pages/tldr/commit/d30ee43e7d48a803c5c3bc369b16e6ba628be9eb)

