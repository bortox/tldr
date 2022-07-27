---
author: ['wizarot', 'Seth Falco', 'Ein Verne', 'bl-ue']
date: 1648358715
title: "xcodebuild, TLDR Pages"
description: "xcodebuild, 构建 Xcode 项目。"
categories: "osx"
---
- 构建工作区：

```bash
xcodebuild -workspace 工作区名.工作区 -scheme 主题名 -configuration 配置名 clean build SYMROOT=SYMROOT_路径
```

- 构建项目：

```bash
xcodebuild -target 目标名 -configuration 配置名 clean build SYMROOT=SYMROOT_路径
```

- 显示 SDK：

```bash
xcodebuild -showsdks
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | xcodebuild: add Chinese translation | 2019-04-01T22:57:41 | [26910e84b039](https://github.com/tldr-pages/tldr/commit/26910e84b039ef6325d1708f1151021e1c66409e)

