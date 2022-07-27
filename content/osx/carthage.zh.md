---
author: ['Kyle', 'bl-ue', 'wizarot', 'Ein Verne', 'Seth Falco']
date: 1648358715
title: "carthage, TLDR Pages"
description: "carthage, Cocoa 应用程序的依赖性管理工具。"
categories: "osx"
---
> 更多信息：<https://github.com/Carthage/Carthage>.

- 下载 Cartfile 中提到的所有依赖项的最新版本，并编译它们：

```bash
carthage update
```

- 仅针对 IOS 平台，升级依赖文件：

```bash
carthage update --platform ios
```

- 仅更新依赖，但不编译它们：

```bash
carthage update --no-build
```

- 下载并重新生成依赖项的当前版本（不更新它们）：

```bash
carthage bootstrap
```

- 重新编译特定依赖项：

```bash
carthage build 依赖包
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | carthage: add Chinese translation | 2019-02-26T19:50:35 | [a2551e9af71f](https://github.com/tldr-pages/tldr/commit/a2551e9af71fde9eabd21e34b6be19648859d5ae)

