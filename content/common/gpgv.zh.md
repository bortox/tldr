---
author: ['Tiny', 'bl-ue', 'marchersimon']
date: 1630394029
title: "gpgv"
description: "gpgv, 验证 OpenPGP 签名。"
categories: "common"
---
> 更多信息：<https://www.gnupg.org/documentation/manuals/gnupg/gpgv.html>.

- 验证签名文件：

```bash
gpgv path/to/file
```

- 使用分离式签名验证已签名的文件：

```bash
gpgv path/to/signature path/to/file
```

- 在 keyrings 列表中添加一个文件（一个导出的钥匙也算作一个 keyring）：

```bash
gpgv --keyring path/to/keyring_file path/to/signature path/to/file
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: fix (valid) tldr-lint errors (#5375) | 2021-03-08T21:22:42 | [7b57b87145b6](https://github.com/tldr-pages/tldr/commit/7b57b87145b67f1642251659b3568739f963754f)
[Tiny](mailto:freelxs@gmail.com) | gpg: add Chinese translation (#5193) | 2021-01-30T04:16:53 | [a52007380f7b](https://github.com/tldr-pages/tldr/commit/a52007380f7b204cda27f91ac3547d85acdab318)

