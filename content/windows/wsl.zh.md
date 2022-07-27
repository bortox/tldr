---
author: ['Flex Zhong', 'bl-ue', 'marchersimon']
date: 1630394029
title: "wsl, TLDR Pages"
description: "wsl, 从命令行管理适用于 Linux 的 Windows 子系统。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows/wsl/reference>.

- 启动 Linux Shell（在默认发行版中）：

```bash
wsl shell_命令
```

- 在不使用 Shell 的情况下运行 Linux 命令：

```bash
wsl --exec 命令 命令参数
```

- 指定特定的发行版：

```bash
wsl --distribution 发行版 shell_命令
```

- 列出所有可用发行版：

```bash
wsl --list
```

- 将发行版导出到 .tar 文件：

```bash
wsl --export 发行版 路径/distro_fs.tar
```

- 从 .tar 文件导入发行版：

```bash
wsl --import 发行版 路径/安装位置 路径/distro_fs.tar
```

- 更改指定发行版的版本：

```bash
wsl --set-version 发行版 版本
```

- 关闭适用于 Linux 的 Windows 子系统：

```bash
wsl --shutdown
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | scoop-bucket, wsl, takeown: add Chinese translation (#4604) * scoop-bucket: add Chinese translation * wsl: add Chinese translation * [...] | 2020-10-12T23:06:25 | [dd2fee0c190e](https://github.com/tldr-pages/tldr/commit/dd2fee0c190e950d33a12941482637e2387216bc)

