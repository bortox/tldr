---
author: ['WhiredPlanck', 'bl-ue', 'marchersimon']
date: 1630394029
title: "acpi, TLDR Pages"
description: "acpi, 显示电池状态或热量信息。"
categories: "linux"
---
> 更多信息：<https://sourceforge.net/projects/acpiclient/files/acpiclient/>.

- 显示电池信息：

```bash
acpi
```

- 显示热量（温度）信息：

```bash
acpi -t
```

- 显示冷却设备信息：

```bash
acpi -c
```

- 用华氏度单位显示热量（温度）信息：

```bash
acpi -tf
```

- 显示所有信息：

```bash
acpi -V
```

- 从 `/proc` 而非 `/sys` 中提取信息：

```bash
acpi -p
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[WhiredPlanck](mailto:47623588+whriedplanck@users.noreply.github.com) | acpi, flatpak, i3, iptables: add Chinese translation (#5061) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-01T23:26:50 | [66da99825c17](https://github.com/tldr-pages/tldr/commit/66da99825c17d7f5c97e61f7eb01218e8edb5449)

