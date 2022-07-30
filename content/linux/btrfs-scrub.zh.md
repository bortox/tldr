---
author: ['Coelacanthus', 'bl-ue', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "btrfs scrub"
description: "btrfs scrub, 清理 btrfs 文件系统以验证数据完整性。"
categories: "linux"
---
> 建议每月运行一次 scrub.

> 更多信息：<https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs-scrub>.

- 开始 scrub：

```bash
sudo btrfs scrub start 指向挂载点的路径
```

- 显示正在进行或上次完成的 scrub 的状态：

```bash
sudo btrfs scrub status 指向挂载点的路径
```

- 取消正在进行的 scrub：

```bash
sudo btrfs scrub cancel 指向挂载点的路径
```

- 恢复先前取消的 scrub：

```bash
sudo btrfs scrub resume 指向挂载点的路径
```

- 开始擦洗，但要等到 scrub 完成后才能退出：

```bash
sudo btrfs scrub start -B 指向挂载点的路径
```

- 在安静模式下启动 scrub（不打印错误或统计信息）：

```bash
sudo btrfs scrub start -q 指向挂载点的路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Coelacanthus](mailto:coelacanthus@outlook.com) | btrfs*: add Chinese translation (#5244) | 2021-05-17T19:36:45 | [93cafcd82102](https://github.com/tldr-pages/tldr/commit/93cafcd8210246b71fd207cf53fc0fceced204ec)

