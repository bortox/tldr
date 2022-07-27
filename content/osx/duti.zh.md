---
author: ['wizarot', 'Kyle', 'Ein Verne', 'bl-ue']
date: 1629747204
title: "duti, TLDR Pages"
description: "duti, 在 macOS 上为文档类型和网页设置默认打开的应用程序。"
categories: "osx"
---
> 更多信息：<https://github.com/moretension/duti>.

- 将 Safari 设置为 HTML 文档的默认打开程序：

```bash
duti -s com.apple.Safari public.html all
```

- 将 vlc 设置为扩展名为.m4v 的文件的默认查看器：

```bash
duti -s org.videolan.vlc m4v viewer
```

- 将 Finder 设置为 ftp:// URL 访问的应用：

```bash
duti -s com.apple.Finder ftp
```

- 显示有关给定扩展名的默认应用程序的信息：

```bash
duti -x ext
```

- 显示给定的 UTI 对应默认的处理程序：

```bash
duti -d uti
```

- 显示给定 UTI 对应所有的处理程序：

```bash
duti -l uti
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | duti: add Chinese translation | 2019-02-26T19:50:35 | [bf3054913104](https://github.com/tldr-pages/tldr/commit/bf3054913104da477e73921176119a339222134d)

