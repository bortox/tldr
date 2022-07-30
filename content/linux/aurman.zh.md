---
author: ['千玄子']
date: 1629942485
title: "aurman"
description: "aurman, 用来构建和安装 AUR 包的 Arch Linux 实用工具。"
categories: "linux"
---
> 参见 `pacman`.

> 更多信息：<https://github.com/polygamma/aurman>.

- 同步并更新所有包：

```bash
aurman --sync --refresh --sysupgrade
```

- 同步并更新所有包但不显示 `PKGBUILD` 文件的变动：

```bash
aurman --sync --refresh --sysupgrade --noedit
```

- 安装一个新包：

```bash
aurman --sync 包名
```

- 安装一个新包但不显示 `PKGBUILD` 文件的变动：

```bash
aurman --sync --noedit 包名
```

- 无确认提示安装一个新包：

```bash
aurman --sync --noedit --noconfirm 包名
```

- 在官方仓库和 AUR 的包数据库中查找关键字：

```bash
aurman --sync --search 关键字
```

- 移除一个包及其依赖：

```bash
aurman --remove --recursive --nosave 包名
```

- 清除包缓存（用两次 `--clean` 参数清除所有包缓存）：

```bash
aurman --sync --clean
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | anbox, arch-chroot, archinstall, aurman: add Chinese translation (#6406) * anbox: add Chinese translation * arch-chroot: add Chinese [...] | 2021-08-26T03:48:05 | [19e79cd10be9](https://github.com/tldr-pages/tldr/commit/19e79cd10be9572d5a8b1dc18a48590c05892280)

