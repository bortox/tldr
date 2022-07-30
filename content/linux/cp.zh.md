---
author: ['errorcode']
date: 1628875176
title: "cp"
description: "cp, 复制文件和目录。"
categories: "linux"
---
> 更多信息：<https://www.gnu.org/software/coreutils/cp>.

- 复制一个文件到另外一个地方：

```bash
cp 文件的原始路径 文件的目标路径
```

- 复制一个文件到另外一个目录, 保持文件名不变：

```bash
cp 文件的原始路径 目标目录路径
```

- 递归的复制一个目录内的内容到另外一个地方（如果目标目录存在，目录被复制到目标目标内部）：

```bash
cp -r 目录的原始路径 目标目录路径
```

- 以详细模式递归的复制一个目录 (当文件被复制的时候显示)：

```bash
cp -vr 文件的原始路径 目标目录路径
```

- 以交互模式复制文本文件到另外一个地方（在覆盖之前提示用户）：

```bash
cp -i *.txt 目标目录路径
```

- 跟踪软连接复制：

```bash
cp -L 链接 目标目录路径
```

- 使用原始文件的全路径，在复制的时候目录不存在则离开创建：

```bash
cp --parents 文件的原始路径 文件的目标路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[errorcode](mailto:errorcode7@qq.com) | cp, grub-install, grub-mkconfig, hexdump, readelf: add Chinese translation (#6278) | 2021-08-13T19:19:36 | [39b5be991a84](https://github.com/tldr-pages/tldr/commit/39b5be991a84323b8fa746ce688cf044240b9752)

