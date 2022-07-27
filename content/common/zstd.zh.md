---
author: ['KsRyY', 'Ein Verne', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon']
date: 1630394029
title: "zstd, TLDR Pages"
description: "zstd, 使用 Zstandard 压缩来压缩 / 解压文件。"
categories: "common"
---
> 更多信息：<https://github.com/facebook/zstd>.

- 将一个文件压缩到一个 `.zst` 后缀的压缩文件中：

```bash
zstd file
```

- 解压缩一个文件：

```bash
zstd -d file.zst
```

- 将文件解压缩到标准输出（stdout）：

```bash
zstd -dc file.zst
```

- 使用指定的压缩等级来压缩一个文件.0 = 最差，19 = 最好（默认等级是 3）：

```bash
zstd -level file
```

- 使用更多内存（解压或压缩时）来得到更高的压缩比：

```bash
zstd --ultra -level file
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[KsRyY](mailto:andy200511@126.com) | zstd: add Chinese translation | 2019-08-26T02:09:41 | [51b9725280e0](https://github.com/tldr-pages/tldr/commit/51b9725280e0d5dce379bdf8496a75944085bc0f)

