---
author: ['bl-ue', 'wizarot', 'meowmeowcat', 'Ein Verne', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1648358715
title: "textutil, TLDR Pages"
description: "textutil, 用于操作各种格式的文本文件。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/textutil.html>.

- 显示有关 `foo.rtf` 的信息：

```bash
textutil -info foo.rtf
```

- 将 `foo.rtf` 转换为 `foo.html`：

```bash
textutil -convert html foo.rtf
```

- 将带格式的 rtf 文本转换为普通 txt 文本：

```bash
textutil foo.rtf -convert txt
```

- 将 `foo.txt` 转换为 `foo.rtf`, 字体使用 Times 字号 10：

```bash
textutil -convert rtf -font Times -fontsize 10 foo.txt
```

- 加载当前目录中的所有 RTF 文件，连接其内容，并将结果作为 `index.html` 写入，HTML 标题设置为"多个文件"：

```bash
textutil -cat html -title "多个文件" -output index.html *.rtf
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | textutil, top: add link (#7629) | 2022-01-14T13:59:47 | [e2f4d81f6bd4](https://github.com/tldr-pages/tldr/commit/e2f4d81f6bd48fe667d0659b5cb165a2244c9f54)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | txtutil: add Chinese translation | 2019-04-01T22:57:41 | [30eb42b4c1b9](https://github.com/tldr-pages/tldr/commit/30eb42b4c1b9637feae49d9e085c2be417ad530f)

