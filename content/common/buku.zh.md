---
author: ['zhouquan', 'bl-ue', 'marchersimon']
date: 1630394029
title: "buku, TLDR Pages"
description: "buku, 命令行版本的书签管理器。"
categories: "common"
---
> 更多信息：<https://github.com/jarun/Buku>.

- 根据关键词和标签查找书签：

```bash
buku 关键字 --stag 标签
```

- 添加书签，并且打上标签：

```bash
buku --add https://example.com 搜索引擎, 标签
```

- 删除一个书签：

```bash
buku --delete "书签 id"
```

- 打开编辑器，修改书签：

```bash
buku --write "书签 id"
```

- 将指定标签移除：

```bash
buku --update "书签 id" --tag - 搜索引擎
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

