---
author: ['Tiny', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "gpg-zip, TLDR Pages"
description: "gpg-zip, 使用`GPG`加密存档中的文件和目录。"
categories: "common"
---
> 更多信息：<https://www.gnupg.org/documentation/manuals/gnupg/gpg_002dzip.html>.

- 使用密码将一个目录加密为`archive.gpg`：

```bash
gpg-zip --symmetric --output archive.gpg path/to/directory
```

- 将`archive.gpg`解密到同名目录中：

```bash
gpg-zip --decrypt path/to/archive.gpg
```

- 列出加密的`archive.gpg`的内容：

```bash
gpg-zip --list-archive path/to/archive.gpg
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: fix (valid) tldr-lint errors (#5375) | 2021-03-08T21:22:42 | [7b57b87145b6](https://github.com/tldr-pages/tldr/commit/7b57b87145b67f1642251659b3568739f963754f)
[Tiny](mailto:freelxs@gmail.com) | gpg: add Chinese translation (#5193) | 2021-01-30T04:16:53 | [a52007380f7b](https://github.com/tldr-pages/tldr/commit/a52007380f7b204cda27f91ac3547d85acdab318)

