---
author: ['errorcode']
date: 1628875176
title: "readelf"
description: "readelf, 显示 EFI 文件信息。"
categories: "linux"
---
> 更多信息：<http://man7.org/linux/man-pages/man1/readelf.1.html>.

- 显示 ELF 所有文件信息：

```bash
readelf -all path/to/binary
```

- 显示 ELF 文件的所有头信息：

```bash
readelf --headers path/to/binary
```

- 如果存在符号表项，则显示 ELF 文件内的符号表项：

```bash
readelf --symbols path/to/binary
```

- 显示 ELF 文件头信息：

```bash
readelf --file-header path/to/binary
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[errorcode](mailto:errorcode7@qq.com) | cp, grub-install, grub-mkconfig, hexdump, readelf: add Chinese translation (#6278) | 2021-08-13T19:19:36 | [39b5be991a84](https://github.com/tldr-pages/tldr/commit/39b5be991a84323b8fa746ce688cf044240b9752)

