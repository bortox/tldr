---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'meowmeowcat']
date: 1635858124
title: "xattr"
description: "xattr, 用于扩展文件系统属性的实用程序。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/xattr.html>.

- 列出 键：值 列表，显示指定文件的值扩展属性：

```bash
xattr -l 文件名
```

- 为给定文件写入属性：

```bash
xattr -w 属性键名 属性值 文件名
```

- 从给定文件中删除属性：

```bash
xattr -d com.apple.quarantine 文件名
```

- 从给定文件中删除所有扩展属性：

```bash
xattr -c 文件名
```

- 递归删除给定目录中文件的属性：

```bash
xattr -rd 属性键名 目录
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | xattr: add Chinese translation | 2019-04-01T22:57:41 | [9c857c99be87](https://github.com/tldr-pages/tldr/commit/9c857c99be871a4e77f8d694e0b43e891e7e06bd)

