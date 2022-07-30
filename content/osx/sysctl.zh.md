---
author: ['meowmeowcat', 'Ein Verne', 'NashMiao', 'wizarot', 'bl-ue']
date: 1636919159
title: "sysctl"
description: "sysctl, 访问内核状态信息。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/sysctl.html>.

- 显示所有可用变量及其值：

```bash
sysctl -a
```

- 显示 Apple 型号标识符：

```bash
sysctl -n hw.model
```

- 显示 CPU 模型：

```bash
sysctl -n machdep.cpu.brand_string
```

- 显示可用的 CPU 功能（MMX, SSE, SSE2, SSE3, AES, 等）：

```bash
sysctl -n machdep.cpu.features
```

- 设置一个可更改的内核状态变量：

```bash
sysctl -w 部分。可修改的变量=值
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[NashMiao](mailto:18191964+NashMiao@users.noreply.github.com) | sysctl: fix typo (#4184) * Fix wrong option * Update sysctl.md | 2020-07-16T20:44:50 | [7c4aab2566fe](https://github.com/tldr-pages/tldr/commit/7c4aab2566fe77e489bf61877a34f076e06e7422)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | sysctl: add Chinese translation | 2019-03-15T12:47:29 | [bf4f523d6d7e](https://github.com/tldr-pages/tldr/commit/bf4f523d6d7ed18ddf725d152c9fc3b5db073a20)

