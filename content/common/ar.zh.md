---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1630394029
title: "ar, TLDR Pages"
description: "ar, 创建，修改，提取库文件（`.a`, `.so`, `.o`）。"
categories: "common"
---
> 更多信息：<https://manned.org/ar>.

- 从库文件中提取全部成员：

```bash
ar -x a 文件
```

- 列出库文件中的成员：

```bash
ar -t a 文件
```

- 替换或添加文件到库文件：

```bash
ar -r 要被添加内容的 a 文件 o 文件 1 o 文件 2 o 文件 3
```

- 插入对象文件索引（相当于使用`ranlib`）：

```bash
ar -s a 文件
```

- 使用文件和附带的目标文件索引创建存档：

```bash
ar -rs a 文件 o 文件 1 o 文件 2 o 文件 3
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-18T16:33:27 | [3c2cf700535c](https://github.com/tldr-pages/tldr/commit/3c2cf700535c96240fc4832e5c1e117c6e4b696d)
[marchersimon](mailto:marchersimon@zohomail.eu) | ar: add link | 2021-04-18T16:33:27 | [bc1219f3c90d](https://github.com/tldr-pages/tldr/commit/bc1219f3c90dc2328626e04ab6496ddd8f0405d3)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | ar: add Chinese translation | 2019-04-17T21:44:55 | [801f431f2792](https://github.com/tldr-pages/tldr/commit/801f431f27926fecceab00b78395f4856f10500b)
[Starccy](mailto:452276725@qq.com) | ar: ar: add Chinese translation | 2019-04-17T21:44:55 | [dc13a4b7b863](https://github.com/tldr-pages/tldr/commit/dc13a4b7b863576956a02d2cff5d44f5439788b3)

