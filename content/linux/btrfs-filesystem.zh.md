---
author: ['Coelacanthus', 'bl-ue', 'marchersimon']
date: 1630394029
title: "btrfs filesystem"
description: "btrfs filesystem, 管理 btrfs 文件系统。"
categories: "linux"
---
> 更多信息：<https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-filesystem>.

- 显示文件系统使用情况（可以选择以 root 身份运行以显示详细信息）：

```bash
btrfs filesystem usage 指向挂载点的路径
```

- 显示各个设备的使用情况：

```bash
sudo btrfs filesystem show 指向挂载点的路径
```

- 对 btrfs 文件系统上的单个文件进行碎片整理（避免在运行数据去重的同时运行）：

```bash
sudo btrfs filesystem defragment -v 指向文件的路径
```

- 递归对目录进行碎片整理（不跨越子卷边界）：

```bash
sudo btrfs filesystem defragment -v -r 指向目录的路径
```

- 强制将未写入的数据块同步到磁盘：

```bash
sudo btrfs filesystem sync 指向挂载点的路径
```

- 递归总结目录中文件的磁盘使用情况：

```bash
sudo btrfs filesystem du --summarize 指向目录的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Coelacanthus](mailto:coelacanthus@outlook.com) | btrfs*: add Chinese translation (#5244) | 2021-05-17T19:36:45 | [93cafcd82102](https://github.com/tldr-pages/tldr/commit/93cafcd8210246b71fd207cf53fc0fceced204ec)

