---
author: ['wizarot', 'Kyle', 'Ein Verne', 'bl-ue']
date: 1629747204
title: "chflags, TLDR Pages"
description: "chflags, 更改文件或文件夹的标志。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/chflags.html>.

- 给文件设置 hidden（隐藏）标签：

```bash
chflags hidden 文件路径
```

- 取消文件的 hidden 标签：

```bash
chflags hidden 文件路径
```

- 递归地给文件夹中每个文件设置 uchg 标志：

```bash
chflags -R uchg 文件夹路径
```

- 递归地撤销文件夹中每个文件设置的 uchg 标志：

```bash
chflags -R nouchg 文件夹路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | chflags: add Chinese translation | 2019-02-26T19:50:35 | [a2f0a52e7110](https://github.com/tldr-pages/tldr/commit/a2f0a52e7110c82000ba606291878383ad6bd15e)

