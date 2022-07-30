---
author: ['Ein Verne', 'bl-ue', 'KsRyY', 'marchersimon']
date: 1630394029
title: "z"
description: "z, 记录被使用次数最多的目录并允许在它们之间以字符串或正则表达式来进行匹配和跳转。"
categories: "common"
---
> 更多信息：<https://github.com/rupa/z>.

- 跳转到一个名字带有 "foo" 的文件夹：

```bash
z foo
```

- 跳转到一个名字带有 "foo" 并且后面带有 "bar" 的文件夹（例：`fooesbar`）：

```bash
z foo bar
```

- 跳转到名字带有 "foo" 并且拥有最高访问次数的文件夹：

```bash
z -r foo
```

- 跳转到最近使用的名字带有 "foo" 的文件夹：

```bash
z -t foo
```

- 列出在 `z` 的数据库中名字带有 "foo" 的文件夹：

```bash
z -l foo
```

- 将当前文件夹从 `z`的数据库中移除：

```bash
z -x .
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[KsRyY](mailto:andy200511@126.com) | z: add Chinese translation | 2019-08-26T02:09:41 | [ba4d051e322d](https://github.com/tldr-pages/tldr/commit/ba4d051e322d14fd584af47c03702b52560b7f43)

