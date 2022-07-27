---
author: ['Tiny', 'bl-ue', 'Stig124', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "dmenu, TLDR Pages"
description: "dmenu, 动态菜单。"
categories: "linux"
---
> 根据文本输入创建菜单，其中每一项都在新行中。

> 更多信息：<https://manned.org/dmenu>.

- 显示 `ls` 命令输出的菜单：

```bash
ls | dmenu
```

- 显示包含自定义项目的菜单，并用新行（`\n`）分隔：

```bash
echo -e "red\ngreen\nblue" | dmenu
```

- 让用户在多个项目之间进行选择，然后将所选项目保存到文件中：

```bash
echo -e "red\ngreen\nblue" | dmenu > color.txt
```

- 在特定的监视器上启动 `dmenu`：

```bash
ls | dmenu -m 1
```

- 在屏幕底部显示 `dmenu`：

```bash
ls | dmenu -b
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Tiny](mailto:freelxs@gmail.com) | dmenu: add Chinese translation (#5803) | 2021-04-24T15:05:38 | [677a3bcbcb08](https://github.com/tldr-pages/tldr/commit/677a3bcbcb08118099c30eca5945276a22c0b4f1)

