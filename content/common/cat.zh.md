---
author: ['zhouquan', 'Dario Vladović', 'bl-ue', 'marchersimon']
date: 1630394029
title: "cat, TLDR Pages"
description: "cat, 打印和拼接文件的工具。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/cat>.

- 以标准输出，打印文件内容：

```bash
cat file
```

- 多文件合并到目标文件：

```bash
cat file1 file2 > target_file
```

- 多文件合并，并追加到目标文件：

```bash
cat file1 file2 >> target_file
```

- 显示行号：

```bash
cat -n file
```

- 显示不可打印和空白的字符（使用 `M-` 前缀标记非 ASCII 字符）：

```bash
cat -v -t -e file
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

