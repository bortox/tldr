---
author: ['KsRyY', 'Ein Verne', 'lincc', 'bl-ue', 'marchersimon']
date: 1630394029
title: "vim, TLDR Pages"
description: "vim, Vi IMproved，一个程序员的文本编辑器，提供为不同类型的文档修改设计的多种模式。"
categories: "common"
---
> 按 `i` 进入插入模式。`<Esc>` 返回正常模式，正常模式允许使用 Vim 命令。

> 更多信息：<https://www.vim.org>.

- 打开文档：

```bash
vim 文件
```

- 打开文件的指定行数：

```bash
vim +行数 文件
```

- 查看 Vim 的使用说明：

```bash
:help<Enter>
```

- 保存并退出：

```bash
:wq<Enter>
```

- 撤销上一个操作：

```bash
u
```

- 用特征（pattern）在文件中搜寻，按下 `n`/`N` 切换至上 / 下一个结果：

```bash
/特征<Enter>
```

- 对整个文件使用正则表达式进行替换：

```bash
:%s/正则表达式/替换字/g<Enter>
```

- 显示行号：

```bash
:set nu<Enter>
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | vim: refresh (#6375) | 2021-08-17T20:11:25 | [4ba58f514ad8](https://github.com/tldr-pages/tldr/commit/4ba58f514ad8d22c477708ccc673453bf583a0cb)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[KsRyY](mailto:andy200511@126.com) | vim: add Chinese translation and some tips | 2019-08-26T02:09:41 | [6ba7e6571ab9](https://github.com/tldr-pages/tldr/commit/6ba7e6571ab9c7b98598d99e934f261e521fe5e3)

