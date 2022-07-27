---
author: ['marchersimon', 'bl-ue', 'lincc', 'xiaolong']
date: 1643487459
title: "rsync, TLDR Pages"
description: "rsync, 一种快速，通用，远程（和本地）文件复制工具。"
categories: "common"
---
> 更多信息：<https://manned.org/rsync>.

- 从本地传输文件到远程主机：

```bash
rsync path/to/local_file remote_host:path/to/remote_directory
```

- 从远程主机传输文件到本地：

```bash
rsync remote_host:path/to/remote_file path/to/local_directory
```

- 将本地文件以归档模式并保留几乎所有属性，同时使用压缩功能传输到远程主机，并以人类可读方式输出详细信息和进度条：

```bash
rsync --archive --compress --verbose --human-readable --progress path/to/local_file remote_host:path/to/remote_directory
```

- 将远程主机目录上的所有文件，以递归模式传输到本地：

```bash
rsync --recursive remote_host:path/to/remote_directory path/to/local_directory
```

- 将远程主机该目录下的所有内容（不包含该目录），以递归方式传输到本地：

```bash
rsync --recursive remote_host:path/to/remote_directory/ path/to/local_directory
```

- 递归方式传输目录，保留几乎所有属性，解析软连接，并忽略已传输的文件：

```bash
rsync --recursive --archive --update --copy-links remote_host:path/to/remote_file path/to/local_directory
```

- 指定本地和远程之间通信方式：

```bash
rsync --rsh ssh remote_host:path/to/remote_file path/to/local_file
```

- 指定本地和远程之间通信方式，使用指定端口，并显示进度条：

```bash
rsync --rsh 'ssh -p port' --progress remote_host:path/to/remote_file path/to/local_file
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[xiaolong](mailto:65013593+xiaolong-666@users.noreply.github.com) | rsync: add Chinese translation (#5200) | 2021-02-02T12:13:06 | [d698531e94cb](https://github.com/tldr-pages/tldr/commit/d698531e94cb145e16e8d20938077cf9c1844ffd)

