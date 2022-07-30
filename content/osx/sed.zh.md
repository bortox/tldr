---
author: ['Cristobal Forno', 'Ein Verne', 'wizarot', 'bl-ue', 'marchersimon']
date: 1630394029
title: "sed"
description: "sed, 以可用脚本的来批量编辑文本。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/sed.html>.

- 替换文件中第一个出现的字符串，并打印结果：

```bash
sed 's/查找内容/替换内容/' 文件名
```

- 替换文件中所有符合正则表达式的部分：

```bash
sed -E 's/正则表达式/替换内容/g' 文件名
```

- 替换文件中所有出现的字符串，覆盖文件（直接覆盖文件）：

```bash
sed --in-place='' 's/查找内容/替换内容/g' 文件名
```

- 仅替换与行模式（一种搜索条件）匹配的行内容：

```bash
sed '/行模式/s/查找内容/替换内容/' 文件名
```

- 只打印第 n 行到下一行之间的文本：

```bash
sed -n '行号,/^$/p' 文件名
```

- 将多个查找替换表达式应用于文件：

```bash
sed -e 's/查找内容/替换内容/' -e 's/查找内容/替换内容/' 文件名
```

- 将分隔符 / 替换为查找或替换模式中没有用到的的任何其他字符，例如 #（用于查找或替换内容中使用了 / 的情况）：

```bash
sed 's#查找内容#替换内容#' 文件名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | osx/sed: add link (#5535) | 2021-03-30T11:00:13 | [dc0617c0623f](https://github.com/tldr-pages/tldr/commit/dc0617c0623fc0d1a798892a02a7f20c55a28f2b)
[Cristobal Forno](mailto:cforno1@binghamton.edu) | sed: minor syntax fix (#3908) | 2020-03-18T22:23:45 | [32997ccf6b2b](https://github.com/tldr-pages/tldr/commit/32997ccf6b2b7aea552d7b4427793c3742b6c9f1)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | sed: add Chinese translation | 2019-03-15T12:47:29 | [0b7ef9189d07](https://github.com/tldr-pages/tldr/commit/0b7ef9189d071027a90d4778135e06f0dc8481c3)

