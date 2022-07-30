---
author: ['marchersimon']
date: 1633112881
title: "brew cask"
description: "brew cask, macOS 上的应用程序包管理工具。"
categories: "common"
---
> 更多信息：<https://github.com/Homebrew/homebrew-cask>.

- 模糊搜索可用命令行工具和软件包：

```bash
brew search 软件名
```

- 安装一个软件：

```bash
brew cask install 软件名
```

- 列出全部已安装软件：

```bash
brew cask list
```

- 列出全部已安装的软件中，可以升级的：

```bash
brew cask outdated
```

- 将一个已安装的软件升级到最新的版本：

```bash
brew cask upgrade 软件名
```

- 删除一个软件（仅通过 brew cask install 方式安装的）：

```bash
brew cask uninstall 软件名
```

- 卸载一个软件并删除相关的设置和文件：

```bash
brew cask zap 软件名
```

- 显示指定软件的相关信息：

```bash
brew cask info 软件名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | brew*: move to common (#6507) | 2021-09-13T09:06:52 | [4fbb601f63ee](https://github.com/tldr-pages/tldr/commit/4fbb601f63ee14b0ed9a23d1d9c78bb102a23776)

