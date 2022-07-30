---
author: ['Stig124', 'lmh', 'Ein Verne', 'Marco Bonelli', 'bl-ue', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "aspell"
description: "aspell, 交互式拼写检查工具。"
categories: "linux"
---
> 更多信息：<http://aspell.net/>.

- 为一个文件做拼写检查：

```bash
aspell check 文件路径
```

- 列出来自标准输入的拼写错误单词：

```bash
cat 文件 | aspell list
```

- 列出可用的字典语言：

```bash
aspell dicts
```

- 指定不同的语言（取 ISO 639 语言代码的 2 个字母）来运行 aspell：

```bash
aspell --lang=cs
```

- 列出来自标准输入的拼写错误单词，并且忽略个人单词列表中的单词：

```bash
cat 文件 | aspell --personal=个人单词列表.pws 列表
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | archey, arp-scan, as, aspell, at: remove execute permission (#5243) | 2021-02-11T14:08:59 | [de72bdb4f8da](https://github.com/tldr-pages/tldr/commit/de72bdb4f8dab69bee04f4cd80bdab935c90f654)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | refactor: fix newlines removing carriage returns (#2880) | 2019-04-10T11:49:16 | [51e3430a3883](https://github.com/tldr-pages/tldr/commit/51e3430a3883b604de4f986f80368e9252c65b94)
[lmh](mailto:hugue_liu@yahoo.com) | aspell: add Chinese translation. | 2019-02-13T16:10:51 | [8f1643124120](https://github.com/tldr-pages/tldr/commit/8f16431241201a7af1728e05eb27cf46ff57aacc)

