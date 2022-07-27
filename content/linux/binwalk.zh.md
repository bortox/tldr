---
author: ['千玄子', 'Seth Falco']
date: 1648358715
title: "binwalk, TLDR Pages"
description: "binwalk, 固件分析工具。"
categories: "linux"
---
> 更多信息：<https://github.com/ReFirmLabs/binwalk>.

- 扫描一个二进制文件：

```bash
binwalk 二进制文件
```

- 解压一个二进制文件并指定输出目录：

```bash
binwalk --extract --directory 输出目录 二进制文件
```

- 递归解压一个二进制文件并限制递归深度为 2：

```bash
binwalk --extract --matryoshka --depth 2 二进制文件
```

- 解压一个二进制文件并指定文件签名：

```bash
binwalk --dd 'png image:png' 二进制文件
```

- 分析一个二进制文件的熵，用与文件相同的名字和 `.png` 后缀保存绘图：

```bash
binwalk --entropy --save 二进制文件
```

- 在单条命令中组合熵、签名和操作码分析：

```bash
binwalk --entropy --signature --opcodes 二进制文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

