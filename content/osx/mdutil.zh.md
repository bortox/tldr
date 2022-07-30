---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'meowmeowcat']
date: 1635959386
title: "mdutil"
description: "mdutil, 管理 Spotlight（聚焦搜索）用于搜索的索引数据。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/mdutil.html>.

- 显示指定卷（'/'）的索引状态：

```bash
mdutil -s /
```

- 打开 / 关闭给定卷的 Spotlight 索引：

```bash
mdutil -i on|off 指定卷文件夹
```

- 清除索引数据并重新建立索引：

```bash
mdutil -E 指定卷文件夹
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/m*: add more information link (#7371) | 2021-11-03T18:09:46 | [1e75baed72db](https://github.com/tldr-pages/tldr/commit/1e75baed72db8bc67f7edfc001cd572f755beba5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | mdutil: add Chinses translation | 2019-03-05T09:15:04 | [5833f36de9b2](https://github.com/tldr-pages/tldr/commit/5833f36de9b22ae9fe41a990fcbcc6c759e56256)

