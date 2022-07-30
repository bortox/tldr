---
author: ['Coelacanthus', 'Stig124', 'marchersimon']
date: 1631521281
title: "btrfs"
description: "btrfs, 一种基于写时复制（COW）原理的 Linux 文件系统。"
categories: "linux"
---
> 此命令也有关于其子命令的文件，例如：`btrfs device`.

> 更多信息：<https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs>.

- 创建子卷：

```bash
sudo btrfs subvolume create 指向子卷的路径
```

- 列出子卷：

```bash
sudo btrfs subvolume list 指向挂载点的路径
```

- 显示空间使用情况信息：

```bash
sudo btrfs filesystem df 指向挂载点的路径
```

- 启用配额（quota）：

```bash
sudo btrfs quota enable 指向子卷的路径
```

- 显示配额（quota）：

```bash
sudo btrfs qgroup show 指向子卷的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Coelacanthus](mailto:coelacanthus@outlook.com) | btrfs*: add Chinese translation (#5244) | 2021-05-17T19:36:45 | [93cafcd82102](https://github.com/tldr-pages/tldr/commit/93cafcd8210246b71fd207cf53fc0fceced204ec)

