---
author: ['Xie Yang', 'Reinhart Previano Koentjoro', 'Patrice Denis', '千玄子', 'Ein Verne', 'hugue', 'bl-ue', 'marchersimon']
date: 1649927229
title: "apt, TLDR Pages"
description: "apt, 基于 Debian 的发行版上的软件包管理工具。"
categories: "linux"
---
> 在 Ubuntu 16.04 及之后版本推荐用它代替 `apt-get` 。

> 更多信息：<https://manpages.debian.org/latest/apt/apt.8.html>.

- 更新可用软件包及其版本列表（推荐在运行其他 apt 命令前首先运行该命令）：

```bash
sudo apt update
```

- 查找指定软件包：

```bash
apt search 软件包
```

- 显示关于指定软件包的信息：

```bash
apt show 软件包
```

- 安装指定软件包或将指定软件包更新到最新版本：

```bash
sudo apt install 软件包
```

- 移除指定软件包（使用 `purge` 同时移除其配置文件）：

```bash
sudo apt remove 软件包
```

- 将所有已安装软件包更新到最新可用版本：

```bash
sudo apt upgrade
```

- 列出所有软件包：

```bash
apt list
```

- 列出已安装的软件包：

```bash
apt list --installed
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Xie Yang](mailto:1023515576@qq.com) | fix: Correct a translation error (#8004) Previously, it means "It is better to use apt-get in Ubuntu versions 16.04 and later." Now, [...] | 2022-04-14T11:07:09 | [9c115e834f85](https://github.com/tldr-pages/tldr/commit/9c115e834f85d4e0a3c7d6c468b14ce3128d160a)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | apt: add backticks to apt-get (#7620) | 2022-01-08T03:15:33 | [e97d77689ab9](https://github.com/tldr-pages/tldr/commit/e97d77689ab99cfb2860768a9a50a0a65a4e03bd)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[千玄子](mailto:ownbyzjuyk@gmail.com) | adduser, apt-*, apt, aptitude, at: update Chinese translation (#6400) | 2021-08-23T21:25:59 | [ff74227350e9](https://github.com/tldr-pages/tldr/commit/ff74227350e9b89a9501ddbf39089ed60876201c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[hugue](mailto:hugue_liu@yahoo.com) | move Chinese pages from pages.cn to pages.zh Also add new Chinese translations for apt, aptitude and arch. | 2019-01-09T05:33:44 | [11f109b466cf](https://github.com/tldr-pages/tldr/commit/11f109b466cf35daefdde57a1ca2e0261f90555c)

