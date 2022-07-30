---
author: ['errorcode', 'Seth Falco']
date: 1648358715
title: "grub-install"
description: "grub-install, 安装 GRUB 到设备。"
categories: "linux"
---
> 更多信息：<https://www.gnu.org/software/grub/manual/grub/html_node/Installing-GRUB-using-grub_002dinstall.html>.

- 安装 GRUB 到基于 BIOS 的系统：

```bash
grub-install --target=i386-pc /dev/sdX
```

- 安装 GRUB 到基于 UEFI 的系统：

```bash
grub-install --target=x86_64-efi --efi-directory=path/to/efi_directory --bootloader-id=GRUB
```

- 安装预置指定模块的 GRUB：

```bash
grub-install --target=x86_64-efi --efi-directory=path/to/efi_directory --modules="part_gpt part_msdos"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[errorcode](mailto:errorcode7@qq.com) | cp, grub-install, grub-mkconfig, hexdump, readelf: add Chinese translation (#6278) | 2021-08-13T19:19:36 | [39b5be991a84](https://github.com/tldr-pages/tldr/commit/39b5be991a84323b8fa746ce688cf044240b9752)

