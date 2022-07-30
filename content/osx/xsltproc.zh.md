---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'lincc']
date: 1643487459
title: "xsltproc"
description: "xsltproc, 用 XSLT 转换 XML 以生成输出（通常是 HTML 或 XML）。"
categories: "osx"
---
> 更多信息：<http://www.xmlsoft.org/xslt/xsltproc.html>.

- 使用特定的 XSLT 样式表转换 XML 文件：

```bash
xsltproc --output 输出.html 样式表.xslt xml 文件.xml
```

- 将值传递给样式表中的参数：

```bash
xsltproc --output 输出.html --stringparam 键名 值 样式表.xslt xml 文件.xml
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | xsltproc: add Chinese translation | 2019-04-01T22:57:41 | [be04f68f299c](https://github.com/tldr-pages/tldr/commit/be04f68f299c7ff6252f80451a9e637e132c6b07)

