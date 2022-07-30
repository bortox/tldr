---
author: ['Managor']
date: 1614521540
title: "grub-install"
description: "grub-install, Install GRUB to a device."
categories: "linux"
---
> More information: <https://www.gnu.org/software/grub/manual/grub/html_node/Installing-GRUB-using-grub_002dinstall.html>.

- Install GRUB on a BIOS system:

```bash
grub-install --target=i386-pc path/to/device
```

- Install GRUB on an UEFI system:

```bash
grub-install --target=x86_64-efi --efi-directory=path/to/efi_directory --bootloader-id=GRUB
```

- Install GRUB pre-loading specific modules:

```bash
grub-install --target=x86_64-efi --efi-directory=path/to/efi_directory --modules="part_gpt part_msdos"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | grub-install, grub-mkconfig: add page (#5261) | 2021-02-28T15:12:20 | [6c37d8813cb2](https://github.com/tldr-pages/tldr/commit/6c37d8813cb278d3d2d63b1bfe641a93c4d1ebaa)

