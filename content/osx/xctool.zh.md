---
author: ['wizarot', 'bl-ue', 'marchersimon']
date: 1633112881
title: "xctool"
description: "xctool, 用于构建 Xcode 项目的工具。"
categories: "osx"
---
> 更多信息：<https://github.com/facebook/xctool>.

- 在没有任何工作区的情况下生成单个项目：

```bash
xctool -project 你的项目.名称 -scheme 方案 build
```

- 构建属于工作区的项目：

```bash
xctool -workspace 你的工作区.名字 -scheme 方案 build
```

- 清理、构建和执行所有测试：

```bash
xctool -workspace 你的工作区.名字 -scheme 方案 clean build test
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[wizarot](mailto:wizarot@qq.com) | xctool: add Chinese translation | 2019-04-01T22:57:41 | [e6b3dee5f7e7](https://github.com/tldr-pages/tldr/commit/e6b3dee5f7e72a76a12da6d37485ba014c17daa4)

