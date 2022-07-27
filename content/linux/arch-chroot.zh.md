---
author: ['千玄子']
date: 1629942485
title: "arch-chroot, TLDR Pages"
description: "arch-chroot, 辅助 Arch Linux 安装流程的更强 `chroot` 命令。"
categories: "linux"
---
> 更多信息：<https://man.archlinux.org/man/arch-chroot.8>.

- 在新的根目录下开启一个交互外壳程序（默认是 `bash`）：

```bash
arch-chroot 新根目录
```

- 指定除当前用户外的其他用户来运行外壳程序：

```bash
arch-chroot -u 用户名 新根目录
```

- 在新的根目录下运行一个自定义命令（取代默认的 `bash`）：

```bash
arch-chroot 新根目录 命令 命令参数
```

- 指定除默认的 `bash` 以外的外壳程序（以下例子需要现在目标系统中先安装 `zsh`）：

```bash
arch-chroot 新根目录 zsh
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | anbox, arch-chroot, archinstall, aurman: add Chinese translation (#6406) * anbox: add Chinese translation * arch-chroot: add Chinese [...] | 2021-08-26T03:48:05 | [19e79cd10be9](https://github.com/tldr-pages/tldr/commit/19e79cd10be9572d5a8b1dc18a48590c05892280)

