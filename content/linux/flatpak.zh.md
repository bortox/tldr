---
author: ['WhiredPlanck', 'Stig124', 'meowmeowcat', 'marchersimon']
date: 1635945210
title: "flatpak"
description: "flatpak, 构建、安装和运行 Flatpak 应用和运行时。"
categories: "linux"
---
> 更多信息：<https://docs.flatpak.org/en/latest/flatpak-command-reference.html#flatpak>.

- 运行已安装应用：

```bash
flatpak run 应用名
```

- 从远程源安装应用：

```bash
flatpak install 远程源名 应用名
```

- 列出所有应用和运行时：

```bash
flatpak list
```

- 更新所有已安装的应用和运行时：

```bash
flatpak update
```

- 添加远程源：

```bash
flatpak remote-add --if-not-exists 远程源名 远程源网址
```

- 列出所有已配置的远程源：

```bash
flatpak remote-list
```

- 移除一个已安装的应用程序：

```bash
flatpak remove 应用名
```

- 显示一个已安装的应用程序的信息：

```bash
flatpak info 应用名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | flatpak: Update Chinese translation (#7332) | 2021-11-03T14:13:30 | [f1ad82543f04](https://github.com/tldr-pages/tldr/commit/f1ad82543f044881aff76ac40371002c6b77c8b8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[WhiredPlanck](mailto:47623588+whriedplanck@users.noreply.github.com) | acpi, flatpak, i3, iptables: add Chinese translation (#5061) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-01T23:26:50 | [66da99825c17](https://github.com/tldr-pages/tldr/commit/66da99825c17d7f5c97e61f7eb01218e8edb5449)

