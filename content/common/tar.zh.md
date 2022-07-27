---
author: ['Tony']
date: 1633265175
title: "tar, TLDR Pages"
description: "tar, 归档实用程序。"
categories: "common"
---
> 通常与压缩方法结合使用，例如 gzip 或 bzip2.

> 更多信息：<https://www.gnu.org/software/tar>.

- 创建存档并将其写入文件：

```bash
tar cf target.tar file1 file2 file3
```

- 创建一个 gzip 压缩文件并将其写入文件：

```bash
tar czf target.tar.gz file1 file2 file3
```

- 使用相对路径从目录创建一个 gzip 压缩文件：

```bash
tar czf target.tar.gz --directory=path/to/directory .
```

- 详细地将（压缩的）存档文件提取到当前目录中：

```bash
tar xvf source.tar[.gz|.bz2|.xz]
```

- 将（压缩的）存档文件解压缩到目标目录中：

```bash
tar xf source.tar[.gz|.bz2|.xz] --directory=directory
```

- 创建压缩存档并将其写入文件，使用存档后缀确定压缩程序：

```bash
tar caf target.tar.xz file1 file2 file3
```

- 详细列出 tar 文件的内容：

```bash
tar tvf source.tar
```

- 从存档文件中提取与模式匹配的文件：

```bash
tar xf source.tar --wildcards "*.html"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Tony](mailto:1462668901@qq.com) | tar: add Chinese translation (#6715) | 2021-10-03T14:46:15 | [9257aed119d5](https://github.com/tldr-pages/tldr/commit/9257aed119d5839a9dd26c3b3562ccafba417763)

