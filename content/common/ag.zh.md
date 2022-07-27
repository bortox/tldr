---
author: ['y1zhou', 'bl-ue', 'Starccy', 'Ein Verne', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "ag, TLDR Pages"
description: "ag, The Silver Searcher. 类似 ack, 但是更快。"
categories: "common"
---
> 更多信息：<https://github.com/ggreer/the_silver_searcher>.

- 寻找内容包含"小明"的文件，并列出所在的行数：

```bash
ag 小明
```

- 在指定目录中寻找内容包含 "foo" 的文件：

```bash
ag 小明 指定的目录
```

- 寻找内容包含 "foo" 的文件，但只列出文件名：

```bash
ag -l 小明
```

- 忽略大小写，寻找内容包含 "ABC" 的文件，并只输出匹配的内容，而非整行：

```bash
ag -i -o ABC
```

- 在文件名包含"小红"的文件中寻找"小明"：

```bash
ag 小明 -G 小红
```

- 使用正则表达式来匹配文件内容：

```bash
ag '^ba(r|z)$'
```

- 输出文件名包含"小明"的文件名：

```bash
ag -g 小明
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[y1zhou](mailto:17245097+y1zhou@users.noreply.github.com) | ag: modify Chinese translation Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-19T18:56:07 | [c4a3ddad26d9](https://github.com/tldr-pages/tldr/commit/c4a3ddad26d9f6356a3301949081678aace95878)
[y1zhou](mailto:zhou.zy.yi@gmail.com) | ag: add link pointing to more information | 2020-10-19T18:56:07 | [f6bed5c8fe23](https://github.com/tldr-pages/tldr/commit/f6bed5c8fe2311b2a2c88d0569312e160982eadf)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | ag: add Chinese translation | 2019-04-17T21:44:55 | [3752a0bc81ae](https://github.com/tldr-pages/tldr/commit/3752a0bc81ae1d253489d74554fef5a6633ccfc8)
[Starccy](mailto:452276725@qq.com) | ag: add Chinese translation | 2019-04-17T21:44:55 | [d69d3ac65799](https://github.com/tldr-pages/tldr/commit/d69d3ac65799bba2d06425198318fdae956a009f)
[Starccy](mailto:452276725@qq.com) | ag: add Chinese translation | 2019-04-17T21:44:55 | [729b5f1008c7](https://github.com/tldr-pages/tldr/commit/729b5f1008c7fcf80982af4bd87d239daf0eb311)

