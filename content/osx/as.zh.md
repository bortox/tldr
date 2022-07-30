---
author: ['Ein Verne', 'wizarot', 'Kyle', 'bl-ue', 'Seth Falco']
date: 1648358715
title: "as"
description: "as, 便携式 GNU 汇编程序。"
categories: "osx"
---
> 主要用于汇编 `gcc` 的输出以供 `ld` 使用。

> 更多信息：<https://www.unix.com/man-page/osx/1/as/>.

- 汇编文件，将输出写入 a.out：

```bash
as 文件.s
```

- 将输出汇编到给定文件：

```bash
as 文件.s -o 输出.o
```

- 通过跳过空白和注释预处理来更快地生成输出.（应该只用于受信任的编译器）：

```bash
as -f 文件.s
```

- 在目录列表中包含一个给定路径，以搜索 .include 指令中指定的文件：

```bash
as -I 目标文件夹 文件.s
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | as: add Chinese translation | 2019-02-26T19:50:35 | [5e79a11ae1e2](https://github.com/tldr-pages/tldr/commit/5e79a11ae1e2ef3d42e540887dd29f5f609e357d)

