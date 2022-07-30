---
author: ['bl-ue', 'BillLucky', 'marchersimon']
date: 1633112881
title: "javadoc"
description: "javadoc, 从源代码以 HTML 格式生成 Java API 文档。"
categories: "common"
---
> 更多信息：<https://docs.oracle.com/javase/9/javadoc/javadoc-command.htm>.

- 生成 Java 源代码的文档并将结果保存在文件夹中：

```bash
javadoc -d path/to/directory/ path/to/java_source_code
```

- 生成指定编码的文档：

```bash
javadoc -docencoding UTF-8 path/to/java_source_code
```

- 生成文档时，排除掉某些软件包：

```bash
javadoc -exclude package_list path/to/java_source_code
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[BillLucky](mailto:bill.libiao@gmail.com) | javadoc: add Chinese translation (#6016) | 2021-05-22T14:40:53 | [b9f699c05521](https://github.com/tldr-pages/tldr/commit/b9f699c05521df0367576a7f0ecc7ffd78af3b92)

