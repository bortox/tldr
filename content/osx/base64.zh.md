---
author: ['Kyle', 'wizarot', 'Ein Verne', 'Matthias Lübken', 'bl-ue']
date: 1629747204
title: "base64, TLDR Pages"
description: "base64, 使用 Base64 来进行编码和解码。"
categories: "osx"
---
> 更多信息：<https://www.unix.com/man-page/osx/1/base64/>.

- 编码目标文件：

```bash
base64 --input=目标文件
```

- 解码目标文件：

```bash
base64 --decode --input=base64 编码文件
```

- 通过标准输入管道进行解码：

```bash
echo -n 目标字符串 | base64
```

- 解码标准输入管道内容：

```bash
echo -n base64 字符串 | base64 --decode
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Matthias Lübken](mailto:matthias.luebken@gmail.com) | base32, base64: fix -D flag (#5234) | 2021-03-07T23:58:11 | [00e00396a42a](https://github.com/tldr-pages/tldr/commit/00e00396a42a8b5fcc189909a1aae3173e513f72)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | base64: add Chinese translation | 2019-02-26T19:50:35 | [2333d1323c8b](https://github.com/tldr-pages/tldr/commit/2333d1323c8b20b2366273abf554e1d47f18e1cc)

