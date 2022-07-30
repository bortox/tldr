---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'meowmeowcat']
date: 1636919159
title: "stat"
description: "stat, 显示文件状态。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/stat.html>.

- 显示文件属性，如大小、权限、创建和访问日期等：

```bash
stat 文件
```

- 与上面相同，但更详细（更类似于 Linux 的 `stat`）：

```bash
stat -x 文件
```

- 只显示文件权限：

```bash
stat -f %Mp%Lp 文件
```

- 显示文件的所有者和所属组：

```bash
stat -f "%Su %Sg" 文件
```

- 以字节为单位显示文件的大小：

```bash
stat -f "%z %N" 文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | stat: add Chinese translation | 2019-03-15T12:47:29 | [e604fb8f18fa](https://github.com/tldr-pages/tldr/commit/e604fb8f18fa31b1163d93cdf065c5193d922047)

