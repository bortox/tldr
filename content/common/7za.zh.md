---
author: ['trolzen', '千玄子', 'Ein Verne', 'bl-ue', 'lmh']
date: 1634591417
title: "7za, TLDR Pages"
description: "7za, 一个高压缩率的文件归档器。"
categories: "common"
---
> 类似于 `7z`，支持的文档类型更少但跨平台。

> 更多信息：<https://www.7-zip.org>.

- 归档一个文件或目录：

```bash
7za a 归档文件.7z 文件或目录
```

- 加密一个已存在的归档文件（包括文件名）：

```bash
7za a 加密文件.7z -p密码 -mhe=on 归档文件.7z
```

- 提取一个已存在的 7z 文件，并保持原来的目录结构：

```bash
7za x 归档文件.7z
```

- 提取一个归档文件到指定目录：

```bash
7za x 归档文件.7z -o输出目录
```

- 提取一个归档文件到标准输出：

```bash
7za x 归档文件.7z -so
```

- 使用指定的类型来归档文件：

```bash
7za a -t7z|bzip2|gzip|lzip|tar|zip 归档文件.7z 文件或目录
```

- 列出一个归档文件的内容：

```bash
7za l 归档文件.7z
```

- 列出可用的归档文件类型：

```bash
7za i
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[trolzen](mailto:trolzen@gmail.com) | 7z, 7za, 7zr: update list of archive formats (#7079) | 2021-10-18T23:10:17 | [1c07b17a6c31](https://github.com/tldr-pages/tldr/commit/1c07b17a6c319eb4d72fd840ee479565893bc3f1)
[千玄子](mailto:ownbyzjuyk@gmail.com) | 7z, 7za, 7zr: update Chinese translation (#6380) | 2021-08-17T19:42:01 | [491fc4f15238](https://github.com/tldr-pages/tldr/commit/491fc4f15238a1451dd91ca98011a8fc6e948253)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[lmh](mailto:hugue_liu@yahoo.com) | 7za: add Chinese translation. | 2019-02-13T16:10:51 | [8f5bee687582](https://github.com/tldr-pages/tldr/commit/8f5bee6875821fa9292298130ed41d28cb91ae17)

