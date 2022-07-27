---
author: ['zhouquan', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "bower, TLDR Pages"
description: "bower, 前端 web 开发的包管理优化工具。"
categories: "common"
---
> 一个包可以是 GitHub 中 user/repo 的缩写，一个 Git 端口，一个 URL 链接或者一个已注册的包。

> 更多信息：<https://bower.io/>.

- 安装列在项目下 的 `bower.json` 文件中的依赖：

```bash
bower install
```

- 安装一个或者多个依赖到 `bower_components` 目录：

```bash
bower install 包名1 包名2
```

- 从本地的 `bower_components` 目录卸载依赖：

```bash
bower uninstall 包名1 包名2
```

- 列出本地包和可能的更新项：

```bash
bower list
```

- 显示 bower 指令的帮助信息：

```bash
bower help 指令
```

- 创建你的项目的 `bower.json`：

```bash
bower init
```

- 安装时候指定依赖的版本号，并添加到 `bower.json`：

```bash
bower install local_name=package#version --save
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

