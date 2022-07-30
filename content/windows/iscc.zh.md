---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1630394029
title: "iscc"
description: "iscc, Inno Setup 安装程序的编译器。"
categories: "windows"
---
> 它将 Inno Setup 脚本编译为 Windows 安装程序可执行文件。

> 更多信息：<https://jrsoftware.org/isinfo.php>.

- 编译一个 Inno Setup 脚本：

```bash
iscc 脚本路径.iss
```

- 静默编译一个 Inno Setup 安装程序：

```bash
iscc /Q 脚本路径.iss
```

- 编译已签名的 Inno Setup 安装程序：

```bash
iscc /S=名称=命令 脚本路径.iss
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:marchersimon@zohomail.eu) | windows: add links | 2021-06-07T21:22:34 | [4755d715b788](https://github.com/tldr-pages/tldr/commit/4755d715b788004b3c86bf0266eee49d19d79d52)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | iscc: add Chinese translation | 2019-03-12T12:56:23 | [d58c61591c42](https://github.com/tldr-pages/tldr/commit/d58c61591c42e1deacb01976b004c9d9d864d3b3)

