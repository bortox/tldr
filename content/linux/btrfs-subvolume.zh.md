---
author: ['Coelacanthus', 'bl-ue', 'marchersimon']
date: 1630394029
title: "btrfs subvolume, TLDR Pages"
description: "btrfs subvolume, 管理 btrfs 子卷和快照。"
categories: "linux"
---
> 更多信息：<https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-subvolume>.

- 创建一个新的空子卷：

```bash
sudo btrfs subvolume create 指向新子卷的路径
```

- 列出指定文件系统中的所有子卷和快照：

```bash
sudo btrfs subvolume list 指向 btrfs 文件系统的路径
```

- 删除一个子卷：

```bash
sudo btrfs subvolume delete 指向子卷的路径
```

- 创建现有子卷的只读快照：

```bash
sudo btrfs subvolume snapshot -r 指向源子卷的路径 指向目标的路径
```

- 创建现有子卷的读写快照：

```bash
sudo btrfs subvolume snapshot 指向源子卷的路径 指向目标的路径
```

- 显示有关子卷的详细信息：

```bash
sudo btrfs subvolume show 指向子卷的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Coelacanthus](mailto:coelacanthus@outlook.com) | btrfs*: add Chinese translation (#5244) | 2021-05-17T19:36:45 | [93cafcd82102](https://github.com/tldr-pages/tldr/commit/93cafcd8210246b71fd207cf53fc0fceced204ec)

