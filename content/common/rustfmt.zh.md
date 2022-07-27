---
author: ['Flex Zhong', 'bl-ue', 'marchersimon']
date: 1630394029
title: "rustfmt, TLDR Pages"
description: "rustfmt, 格式化 Rust 源代码的工具。"
categories: "common"
---
> 更多信息：<https://github.com/rust-lang/rustfmt>.

- 格式化文件，就地覆盖原始文件：

```bash
rustfmt source.rs
```

- 检查文件的格式并在控制台上显示所有更改：

```bash
rustfmt --check source.rs
```

- 格式化之前，备份所有修改过的文件（原始文件的扩展名为 `.bk`）：

```bash
rustfmt --backup source.rs
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | Create rustfmt.md (#4369) | 2020-09-29T12:56:45 | [8803f7ba8ddc](https://github.com/tldr-pages/tldr/commit/8803f7ba8ddc6135caae62ba8b006272b7e79fa6)

