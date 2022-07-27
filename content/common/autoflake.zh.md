---
author: ['zhouquan', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "autoflake, TLDR Pages"
description: "autoflake, 一个工具，用于检查 Python 代码中未被使用的引入和变量。"
categories: "common"
---
> 更多信息：<https://github.com/myint/autoflake>.

- 移除指定文件中未使用的变量，并展示 diff：

```bash
autoflake --remove-unused-variables 文件.py
```

- 移除多个文件中未使用的引入，并展示 diffs：

```bash
autoflake --remove-all-unused-imports 文件1.py 文件2.py 文件3.py
```

- 移除未被使用的变量，并覆盖更新：

```bash
autoflake --remove-unused-variables --in-place 文件.py
```

- 递归地移除指定文件夹下层所有文件中未使用的变量，并覆盖更新：

```bash
autoflake --remove-unused-variables --in-place --recursive 路径/到/目录
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

