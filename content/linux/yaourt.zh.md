---
author: ['Flex Zhong', 'bl-ue', 'Niklas']
date: 1635215179
title: "yaourt, TLDR Pages"
description: "yaourt, Arch Linux 中用于从 Arch User Repository 中构建软件包的工具。"
categories: "linux"
---
> 更多信息：<https://linuxcommandlibrary.com/man/yaourt>.

- 同步并更新所有软件包（包括 AUR）：

```bash
yaourt -Syua
```

- 安装一个新的软件包（包括 AUR）：

```bash
yaourt -S 软件包
```

- 移除一个软件包和它的依赖（包括 AUR 软件包）：

```bash
yaourt -Rs 软件包
```

- 在软件包数据库中搜索一个关键字（包括 AUR）：

```bash
yaourt -Ss 软件包
```

- 列出已安装的软件包、版本和仓库（AUR 软件包将被列在 'local' 仓库下）：

```bash
yaourt -Q
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Niklas](mailto:derNiklaas@users.noreply.github.com) | yank, yaourt: add more information link (#7049) | 2021-10-26T04:26:19 | [bf5c13a00d3b](https://github.com/tldr-pages/tldr/commit/bf5c13a00d3b256646326a4d3bfd23fddc5dbed3)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | yaourt: add chinese (zh) translation (#4150) | 2020-07-05T22:56:12 | [258467d1be2b](https://github.com/tldr-pages/tldr/commit/258467d1be2b7cb5ad979fa35b0302de3c17e327)

