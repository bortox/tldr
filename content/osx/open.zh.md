---
author: ['bl-ue', 'marchersimon', 'Ein Verne', 'wizarot']
date: 1659075216
title: "open, TLDR Pages"
description: "open, 打开文件、目录和应用程序。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/open.html>.

- 使用系统关联的应用程序打开文件：

```bash
open filename.extension
```

- 运行图形化的 macOS 应用程序：

```bash
open -a 应用程序名
```

- 运行指定 包名 的图形化 macOS 应用程序（请参阅`OSascript`命令，查询如何获取应用程序的 包名）：

```bash
open -b com.domain.application 应用程序包名
```

- 在"访达（finder）"中打开当前文件夹：

```bash
open .
```

- 打开"访达（finder）", 并且给出指定文件：

```bash
open -R 文件路径
```

- 使用系统默认应用程序，打开当前目录中所有给定扩展名的文件：

```bash
open *.extension
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | open: add Chinese translation | 2019-03-15T12:47:29 | [e35d8f71e119](https://github.com/tldr-pages/tldr/commit/e35d8f71e1194680f1612bcedfd3255a8fc9445b)

