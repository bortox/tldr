---
author: ['Tiny', 'bl-ue', 'marchersimon']
date: 1633112881
title: "gpg, TLDR Pages"
description: "gpg, GNU Privacy Guard."
categories: "common"
---
> 请参阅`gpg2`了解 GNU Privacy Guard 2.

> 更多信息：<https://gnupg.org>.

- 不加密，仅对`doc.txt`进行签名（生成`doc.txt.asc`，格式为 ASCII 码形式）：

```bash
gpg --clearsign doc.txt
```

- 对`doc.txt`进行签名并加密（生成`doc.txt.asc`，格式为 ASCII 码形式）：

```bash
gpg --local-user sender_id --recipient recipient_id --armor --sign --encrypt doc.txt
```

- 为接收者 alice@example.com 加密`doc.txt`（生成`doc.txt.gpg`）：

```bash
gpg --encrypt --recipient alice@example.com doc.txt
```

- 只用密码加密`doc.txt`（生成`doc.txt.gpg`）：

```bash
gpg --symmetric doc.txt
```

- 解密`doc.txt.gpg`（输出到标准输出）：

```bash
gpg --decrypt doc.txt.gpg
```

- 导入一个公钥：

```bash
gpg --import public.gpg
```

- 导出 alice@example.com 的公钥（输出到标准输出）：

```bash
gpg --export --armor alice@example.com
```

- 导出 alice@example.com 的私钥（输出到标准输出）：

```bash
gpg --export-secret-keys --armor alice@example.com
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: fix (valid) tldr-lint errors (#5375) | 2021-03-08T21:22:42 | [7b57b87145b6](https://github.com/tldr-pages/tldr/commit/7b57b87145b67f1642251659b3568739f963754f)
[Tiny](mailto:freelxs@gmail.com) | gpg: add Chinese translation (#5193) | 2021-01-30T04:16:53 | [a52007380f7b](https://github.com/tldr-pages/tldr/commit/a52007380f7b204cda27f91ac3547d85acdab318)

