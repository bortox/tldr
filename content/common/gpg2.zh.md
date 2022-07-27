---
author: ['Tiny', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "gpg2, TLDR Pages"
description: "gpg2, GNU Privacy Guard 2."
categories: "common"
---
> GNU Privacy Guard 1 请参见`gpg`.

> 更多信息：<https://docs.releng.linuxfoundation.org/en/latest/gpg.html>.

- 列出导入的密钥（公钥）：

```bash
gpg2 --list-keys
```

- 为指定的接收者加密指定的文件，将输出结果写到一个新的文件中，并附加 `.gpg`：

```bash
gpg2 --encrypt --recipient alice@example.com path/to/doc.txt
```

- 只用密码（对称加密）对指定文件进行加密，将输出结果写入一个附加`.gpg`的新文件：

```bash
gpg2 --symmetric path/to/doc.txt
```

- 解密指定的文件，并将结果写入标准输出：

```bash
gpg2 --decrypt path/to/doc.txt.gpg
```

- 导入一个公钥：

```bash
gpg2 --import path/to/public_key.gpg
```

- 将指定电子邮件地址的公钥导出到标准输出：

```bash
gpg2 --export --armor alice@example.com
```

- 将指定电子邮件地址的私钥导出到标准输出：

```bash
gpg2 --export-secret-keys --armor alice@example.com
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: fix (valid) tldr-lint errors (#5375) | 2021-03-08T21:22:42 | [7b57b87145b6](https://github.com/tldr-pages/tldr/commit/7b57b87145b67f1642251659b3568739f963754f)
[Tiny](mailto:freelxs@gmail.com) | gpg: add Chinese translation (#5193) | 2021-01-30T04:16:53 | [a52007380f7b](https://github.com/tldr-pages/tldr/commit/a52007380f7b204cda27f91ac3547d85acdab318)

