---
author: ['marchersimon']
date: 1633112881
title: "file"
description: "file, 确定文件类型。"
categories: "common"
---
> 更多信息：<https://manned.org/file>.

- 提供指定文件类型的描述，对于没有文件扩展名的文件可以正常工作：

```bash
file 文件名
```

- 查看压缩文件并确定其中的文件类型：

```bash
file -z xxx.zip
```

- 允许文件与特殊文件或设备文件一起使用：

```bash
file -s 文件名
```

- 不要在第一个文件类型匹配时停止；继续执行直到文件结束：

```bash
file -k 文件名
```

- 确定文件的 mime 编码类型：

```bash
file -I 文件名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)

