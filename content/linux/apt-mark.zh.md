---
author: ['Patrice Denis', 'Ein Verne', 'hugue', 'bl-ue', 'marchersimon']
date: 1630394029
title: "apt-mark, TLDR Pages"
description: "apt-mark, 修改已安装软件包状态的工具。"
categories: "linux"
---
> 更多信息：<https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- 将一个软件包标记为自动安装：

```bash
sudo apt-mark auto 软件包名
```

- 将一个软件包保持在当前版本，防止对其更新：

```bash
sudo apt-mark hold 软件包名
```

- 允许对一个软件包更新：

```bash
sudo apt-mark unhold 软件包名
```

- 列出手动安装的软件包：

```bash
apt-mark showmanual
```

- 列出保持当前版本而不更新的软件包：

```bash
apt-mark showhold
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[hugue](mailto:hugue_liu@yahoo.com) | move Chinese pages from pages.cn to pages.zh Also add new Chinese translations for apt, aptitude and arch. | 2019-01-09T05:33:44 | [11f109b466cf](https://github.com/tldr-pages/tldr/commit/11f109b466cf35daefdde57a1ca2e0261f90555c)

