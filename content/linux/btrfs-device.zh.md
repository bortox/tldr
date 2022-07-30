---
author: ['Coelacanthus', 'bl-ue', 'marchersimon']
date: 1630394029
title: "btrfs device"
description: "btrfs device, 管理 btrfs 文件系统中的设备。"
categories: "linux"
---
> 更多信息：<https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-device>.

- 将一个或多个设备添加到 btrfs 文件系统中：

```bash
sudo btrfs device add 指向设备1的路径 [指向设备2的路径] 指向 btrfs 文件系统的路径
```

- 从 btrfs 文件系统中删除设备：

```bash
sudo btrfs device remove 指向设备的路径|设备 ID [...]
```

- 显示错误统计：

```bash
sudo btrfs device stats 指向 btrfs 文件系统的路径
```

- 扫描所有磁盘并将所有检测到的 btrfs 文件系统通知内核：

```bash
sudo btrfs device scan --all-devices
```

- 显示详细的每个磁盘的空间分配统计信息：

```bash
sudo btrfs device usage 指向 btrfs 文件系统的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Coelacanthus](mailto:coelacanthus@outlook.com) | btrfs*: add Chinese translation (#5244) | 2021-05-17T19:36:45 | [93cafcd82102](https://github.com/tldr-pages/tldr/commit/93cafcd8210246b71fd207cf53fc0fceced204ec)

