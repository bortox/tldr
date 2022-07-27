---
author: ['Patrice Denis', '千玄子', 'Ein Verne', 'hugue', 'bl-ue', 'marchersimon']
date: 1630394029
title: "apt-get, TLDR Pages"
description: "apt-get, Debian 和 Ubuntu 的软件包管理工具。"
categories: "linux"
---
> 使用 `apt-cache` 查找包。

> 更多信息：<https://manpages.debian.org/latest/apt/apt-get.8.html>.

- 更新可用软件包及其版本列表（推荐在其他 `apt-get` 命令运行之前使用）：

```bash
apt-get update
```

- 安装一个软件包或更新到最新版本：

```bash
apt-get install 软件包
```

- 移除一个软件包：

```bash
apt-get remove 软件包
```

- 移除一个软件包及其配置文件：

```bash
apt-get purge 软件包
```

- 升级所有已安装软件包到最新版本：

```bash
apt-get upgrade
```

- 清理本地仓库 - 移除下载中断后无法再继续下载的（`.deb`）包文件：

```bash
apt-get autoclean
```

- 移除所有不再需要的软件包：

```bash
apt-get autoremove
```

- 升级已安装的软件包（类似于 `upgrade`），移除过时的软件包并安装额外的软件包以满足新的依赖：

```bash
apt-get dist-upgrade
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[千玄子](mailto:ownbyzjuyk@gmail.com) | adduser, apt-*, apt, aptitude, at: update Chinese translation (#6400) | 2021-08-23T21:25:59 | [ff74227350e9](https://github.com/tldr-pages/tldr/commit/ff74227350e9b89a9501ddbf39089ed60876201c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[hugue](mailto:hugue_liu@yahoo.com) | move Chinese pages from pages.cn to pages.zh Also add new Chinese translations for apt, aptitude and arch. | 2019-01-09T05:33:44 | [11f109b466cf](https://github.com/tldr-pages/tldr/commit/11f109b466cf35daefdde57a1ca2e0261f90555c)

