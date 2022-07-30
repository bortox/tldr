---
author: ['bl-ue', 'BillLucky', 'marchersimon']
date: 1633112881
title: "make"
description: "make, Makefile 文件描述目标的任务运行器。"
categories: "common"
---
> 通常用于控制源代码中可执行文件的编译。

> 更多信息：<https://www.gnu.org/software/make/manual/make.html>.

- 调用 Makefile 中指定的第一个目标（通常命名为 "all"）：

```bash
make
```

- 调用指定目标：

```bash
make 目标
```

- 调用一个指定的目标，一次并行执行 4 个作业：

```bash
make -j4 目标
```

- 使用指定的 Makefile 文件：

```bash
make --file 文件
```

- 从另一个目录执行 make ：

```bash
make --directory 文件夹
```

- 即使源文件未更改，也强制执行目标：

```bash
make --always-make 目标
```

- 覆盖在 Makefile 中定义的环境变量：

```bash
make --environment-overrides 目标
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | make: add Chinese translation (#6019) | 2021-05-25T19:25:01 | [cb7ecf03e4bd](https://github.com/tldr-pages/tldr/commit/cb7ecf03e4bd8723c51504a6affaae49352f8e4f)

