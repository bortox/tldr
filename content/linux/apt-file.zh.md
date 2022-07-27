---
author: ['Patrice Denis', '千玄子', 'Ein Verne', 'hugue', 'bl-ue', 'marchersimon']
date: 1630394029
title: "apt-file, TLDR Pages"
description: "apt-file, 在 apt 软件包中查找文件，其中也包括未安装的软件。"
categories: "linux"
---
> 更多信息：<https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- 更新元数据的数据库：

```bash
sudo apt update
```

- 查找包含指定文件或路径的软件包：

```bash
apt-file search|find 文件路径
```

- 列出指定包的内容：

```bash
apt-file show|list 软件包名
```

- 查找符合给定 `pattern` 中正则表达式的软件包：

```bash
apt-file search|find --regexp 正则表达式
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[千玄子](mailto:ownbyzjuyk@gmail.com) | adduser, apt-*, apt, aptitude, at: update Chinese translation (#6400) | 2021-08-23T21:25:59 | [ff74227350e9](https://github.com/tldr-pages/tldr/commit/ff74227350e9b89a9501ddbf39089ed60876201c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[hugue](mailto:hugue_liu@yahoo.com) | move Chinese pages from pages.cn to pages.zh Also add new Chinese translations for apt, aptitude and arch. | 2019-01-09T05:33:44 | [11f109b466cf](https://github.com/tldr-pages/tldr/commit/11f109b466cf35daefdde57a1ca2e0261f90555c)

