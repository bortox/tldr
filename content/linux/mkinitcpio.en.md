---
author: ['Axel Navarro']
date: 1613689794
title: "mkinitcpio, TLDR Pages"
description: "mkinitcpio, Generates initial ramdisk environments for booting the Linux kernel based on the specified preset(s)."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/mkinitcpio.8>.

- Perform a dry run (print what would be done without actually doing it):

```bash
mkinitcpio
```

- Generate a ramdisk environment based on the `linux` preset:

```bash
mkinitcpio --preset linux
```

- Generate a ramdisk environment based on the `linux-lts` preset:

```bash
mkinitcpio --preset linux-lts
```

- Generate ramdisk environments based on all existing presets (used to regenerate all the initramfs images after a change in `/etc/mkinitcpio.conf`):

```bash
mkinitcpio --allpresets
```

- Generate an initramfs image using an alternative configuration file:

```bash
mkinitcpio --config path/to/mkinitcpio.conf --generate path/to/initramfs.img
```

- Generate an initramfs image for a kernel other than the one currently running (the installed kernel releases can be found in `/usr/lib/modules/`):

```bash
mkinitcpio --kernel kernel_version --generate path/to/initramfs.img
```

- List all available hooks:

```bash
mkinitcpio --listhooks
```

- Display help for a specific hook:

```bash
mkinitcpio --hookhelp hook_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | mkinitcpio: add page (#5250) | 2021-02-19T00:09:54 | [2538cef3a2e4](https://github.com/tldr-pages/tldr/commit/2538cef3a2e45c74ab38a41a111190f9e05399d9)

