---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'meowmeowcat']
date: 1635858124
title: "osascript"
description: "osascript, 在命令行中运行指定的 AppleScript 或 JavaScript 脚本程序。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/osascript.html>.

- 运行一个 AppleScript 命令：

```bash
osascript -e 'say "你好世界"'
```

- 运行多条 AppleScript 命令：

```bash
osascript -e 'say "你好"' -e 'say "世界"'
```

- 运行一个已编译的脚本（`*.scpt`），包脚本（`*.scptd`），或明文的（`*.applescript`）AppleScript 文件：

```bash
osascript 目录 / 脚本文件.scpt
```

- 获取应用程序的包名（这个包名，可以用在命令 `open -b` 中）：

```bash
osascript -e 'id of app "应用程序名"'
```

- 运行一个 JavaScript 命令：

```bash
osascript -l JavaScript -e 'console.log("你好世界！");'
```

- 运行 JavaScript 文件：

```bash
osascript -l JavaScript 路径 / 文件名.js
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | osascript: add Chinese translation | 2019-03-15T12:47:29 | [4919bddfc5ee](https://github.com/tldr-pages/tldr/commit/4919bddfc5ee76100d262234102375ec462c0ad4)

