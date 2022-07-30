---
author: ['Ein Verne', 'wizarot', 'bl-ue']
date: 1627893669
title: "popd"
description: "popd, 通过 pushd shell 内置程序删除目录堆栈中的目录。"
categories: "osx"
---
- 从堆栈中删除顶部目录，并用 `cd` 跳转到该目录：

```bash
popd
```

- 删除第 n 个目录（从零开始，以用 `dirs` 打印的列表左侧开始）：

```bash
popd +N
```

- 删除第 n 个目录（从零开始，以用 `dirs` 打印的列表右侧开始）：

```bash
popd -N
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | popd: add Chinese translation | 2019-03-15T12:47:29 | [1a5f1e92418f](https://github.com/tldr-pages/tldr/commit/1a5f1e92418fee073fdeb93a62975ae822e74bff)

