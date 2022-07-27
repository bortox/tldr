---
author: ['Kyle', 'wizarot', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1634848494
title: "du, TLDR Pages"
description: "du, 磁盘使用率：估计和汇总文件和目录空间使用率。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/du.html>.

- 以给定单位（KiB/MiB/GiB）列出目录和所有子目录的大小：

```bash
du -k|m|g 目标文件夹
```

- 以可读形式列出目录和任何子目录的大小（即自动为转换为选择的适当单位 kb|mb|gb）：

```bash
du -h 目标文件夹
```

- 以可读单位显示目录大小：

```bash
du -sh 目标文件夹
```

- 列出目录以及其中所有文件和目录的可读大小：

```bash
du -ah 目标文件夹
```

- 列出一个目录和任何子目录的可读大小，最深可达 n 级：

```bash
du -h -d N 目标文件夹
```

- 列出当前目录子目录中所有.jpg 文件的可读大小，并在末尾显示累计总数：

```bash
du -ch */*.jpg
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: fix wrong byte units (#7131) | 2021-10-21T22:34:54 | [0ddea62ffb82](https://github.com/tldr-pages/tldr/commit/0ddea62ffb822afabf0437c9a0d15258f13ce672)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | du: add Chinese translation | 2019-02-26T19:50:35 | [03208f1db415](https://github.com/tldr-pages/tldr/commit/03208f1db415738d2811a0359a6336efc9a3cffb)

