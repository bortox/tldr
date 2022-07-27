---
author: ['Flex Zhong', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "scoop bucket, TLDR Pages"
description: "scoop bucket, 管理 bucket: 包含描述 scoop 应如何安装应用程序的文件的 Git 存储库。"
categories: "windows"
---
> 如果 Scoop 不知道 bucket 在哪里，则必须指定其存储库位置。

> 更多信息：<https://github.com/lukesampson/scoop/wiki/Buckets>.

- 列出所有正在使用的 bucket：

```bash
scoop bucket list
```

- 列出所有已知 bucket：

```bash
scoop bucket known
```

- 按名称添加一个已知 bucket：

```bash
scoop bucket add 名称
```

- 通过名称和 Git 存储库 URL 添加未知 bucket：

```bash
scoop bucket add 名称 https://example.com/repository.git
```

- 按名称删除 bucket：

```bash
scoop bucket rm 名称
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | scoop-bucket, wsl, takeown: add Chinese translation (#4604) * scoop-bucket: add Chinese translation * wsl: add Chinese translation * [...] | 2020-10-12T23:06:25 | [dd2fee0c190e](https://github.com/tldr-pages/tldr/commit/dd2fee0c190e950d33a12941482637e2387216bc)

