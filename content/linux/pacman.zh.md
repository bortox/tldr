---
author: ['marchersimon', 'bl-ue', 'Axel Navarro', 'Flex Zhong']
date: 1660133637
title: "pacman"
description: "pacman, Arch Linux 的软件包管理器工具。"
categories: "linux"
---
> 更多信息：<https://man.archlinux.org/man/pacman.8>.

- 同步并更新所有软件包：

```bash
sudo pacman -Syu
```

- 安装一个新的软件包：

```bash
sudo pacman -S 软件包
```

- 删除一个软件包及其依赖：

```bash
sudo pacman -Rs 软件包
```

- 在软件包数据库中搜索正则表达式或关键字：

```bash
pacman -Ss "软件包"
```

- 列出已安装的软件包和版本：

```bash
pacman -Q
```

- 仅列出明确安装的软件包和版本：

```bash
pacman -Qe
```

- 查找哪个包拥有某个文件：

```bash
pacman -Qo 文件名
```

- 清空软件包缓存以释放空间：

```bash
sudo pacman -Scc
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: use short options only (#8286) | 2022-08-10T14:13:57 | [1f147d6b91a6](https://github.com/tldr-pages/tldr/commit/1f147d6b91a67044e5f60817a0355d2acd40bb88)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman: add more information link (#5146) | 2021-01-19T15:40:16 | [dbb0e9ef9767](https://github.com/tldr-pages/tldr/commit/dbb0e9ef97671aff87d987e2e67dce8f19d6668a)
[Flex Zhong](mailto:chungzh07@gmail.com) | pacman: add Chinese translation (#4149) | 2020-07-05T22:54:47 | [23e8d310ca04](https://github.com/tldr-pages/tldr/commit/23e8d310ca0437a80d113e336272ce260c90fa83)

