---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "ftp, TLDR Pages"
description: "ftp, 在本地和远程 FTP 服务器之间交互式传输文件。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/ftp>.

- 交互式连接一个远程的 FTP 服务：

```bash
ftp 主机名
```

- 匿名登录：

```bash
ftp -A 主机名
```

- 初始连接时禁用自动登录：

```bash
ftp -n 主机名
```

- 运行包含 FTP 命令列表的文件：

```bash
ftp -s:文件的路径 主机名
```

- 下载多个文件（通配符表达式）：

```bash
mget *.png
```

- 上传多个文件（通配符表达式）：

```bash
mput *.zip
```

- 在远程服务器上删除多个文件：

```bash
mdelete *.txt
```

- 显示详细的帮助：

```bash
ftp --help
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | ftp: add Chinese translation | 2019-03-12T12:56:23 | [c193122f6248](https://github.com/tldr-pages/tldr/commit/c193122f62480a5f23447e4bf4a498ba608df97b)

