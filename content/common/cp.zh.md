---
author: ['bl-ue', 'BillLucky', 'marchersimon']
date: 1630394029
title: "cp"
description: "cp, 复制文件和文件夹。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/cp>.

- 将文件复制到另一个位置：

```bash
cp 某路径/源文件.ext 某路径/目标文件.ext
```

- 将文件复制到另一个文件夹，并保留原来的文件名：

```bash
cp 某路径/源文件.ext 某路径/目标文件夹
```

- 以递归方式将文件夹内的内容复制到另一个位置（如果目标文件夹存在，则将此文件夹复制到目标文件夹中）：

```bash
cp -R 某路径/源文件夹 某路径/目标文件夹
```

- 以详细模式递归复制目录（在复制文件时显示文件信息）：

```bash
cp -vR 某路径/源文件夹 某路径/目标文件夹
```

- 以交互方式将文本文件复制到另一个位置（覆盖之前会提示用户）：

```bash
cp -i *.txt 某路径/目标文件夹
```

- 复制之前，请遵循符号链接：

```bash
cp -L 符号文件 某路径/目标文件夹
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | cp: add Chinese translation (#5877) | 2021-05-07T14:26:51 | [51bf3c73bbec](https://github.com/tldr-pages/tldr/commit/51bf3c73bbec15c7b4042272e75b1ce18fb53dd4)

