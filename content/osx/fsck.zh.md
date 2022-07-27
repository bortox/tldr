---
author: ['wizarot', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "fsck, TLDR Pages"
description: "fsck, 检查或修复文件系统的完整性，运行命令时应卸载文件系统。"
categories: "osx"
---
> 它是一个包装器，包含 `fsck_hfs`, `fsck_apfs`, `fsck_msdos`, `fsck_exfat`, `fsck_udf` 作为可选。

> 更多信息：<https://ss64.com/osx/fsck.html>.

- 检查文件系统 /dev/sda，报告损坏的块：

```bash
fsck /dev/sda
```

- 仅当文件系统 /dev/sda 是干净的时才检查它，报告任何损坏的块并以交互方式让用户选择修复每个块：

```bash
fsck -f /dev/sda
```

- 仅当文件系统 /dev/sda 干净时才检查它，报告任何损坏的块并自动修复它们：

```bash
fsck -fy /dev/sda
```

- 检查文件系统 /dev/sda, 报告是否已完全卸载：

```bash
fsck -q /dev/sda
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | fsck: add Chinese translation | 2019-02-26T19:50:35 | [987fd62062e6](https://github.com/tldr-pages/tldr/commit/987fd62062e6c1ea2ee4ee890afa7ff5d09c8597)

