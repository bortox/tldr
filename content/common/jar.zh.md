---
author: ['BillLucky', 'bl-ue', 'marchersimon']
date: 1633112881
title: "jar, TLDR Pages"
description: "jar, Java 应用程序 / 类库打包程序。"
categories: "common"
---
> 更多信息：<https://docs.oracle.com/javase/tutorial/deployment/jar/basicsindex.html>.

- 将当前目录中的所有文件递归归档到 `.jar` 文件中：

```bash
jar cf file.jar *
```

- 将 `.jar` / `.war` 文件解压缩到当前目录：

```bash
jar -xvf file.jar
```

- 列出 `.jar` / `.war` 文件内容：

```bash
jar tf path/to/file.jar
```

- 列出带有详细输出的 `.jar` / `.war` 文件内容：

```bash
jar tvf path/to/file.jar
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | jar: add Chinese translation (#5977) | 2021-05-17T19:47:25 | [ba782f8b7840](https://github.com/tldr-pages/tldr/commit/ba782f8b7840034202fc666d5479eebba3767ee7)

