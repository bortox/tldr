---
author: ['Ein Verne', 'bl-ue', 'Starccy', 'marchersimon']
date: 1633112881
title: "rdpsign"
description: "rdpsign, 用于签名远程桌面协议（RDP）文件的工具。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/rdpsign>.

- 为一个 RDP 文件签名：

```bash
rdpsign 文件路径.rdp
```

- 使用一个指定的 sha256 哈希值为 RDP 文件签名：

```bash
rdpsign 文件路径.rdp /sha265 哈希值
```

- 启用静默输出：

```bash
rdpsign 文件路径.rdp /q
```

- 显示详细的信息、警告和状态：

```bash
rdpsign 文件路径.rdp /v
```

- 在不更新文件的情况下将输出显示到标准输出来测试签名：

```bash
rdpsign 文件路径.rdp /l
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | rdpsign: add Chinese translation | 2019-03-12T12:56:23 | [3c2bd06329cf](https://github.com/tldr-pages/tldr/commit/3c2bd06329cf63310ec9af13dffcb54d1f31edf9)

