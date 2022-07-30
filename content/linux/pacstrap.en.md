---
author: ['Axel Navarro', 'Waldir Pimenta']
date: 1618918134
title: "pacstrap"
description: "pacstrap, Arch Linux install script to install packages to the specified new root directory."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/pacstrap.8>.

- Install the `base` package, Linux kernel and firmware for common hardware:

```bash
pacstrap path/to/new/root base linux linux-firmware
```

- Install the `base` package, Linux LTS kernel and `base-devel` build tools:

```bash
pacstrap path/to/new/root base base-devel linux-lts
```

- Install packages without copy the host's mirrorlist to the target:

```bash
pacstrap -M path/to/new/root packages
```

- Use an alternate configuration file for Pacman:

```bash
pacstrap -C path/to/pacman.conf path/to/new/root packages
```

- Install packages using the package cache on the host instead of on the target:

```bash
pacstrap -c path/to/new/root packages
```

- Install packages without copy the host's pacman keyring to the target:

```bash
pacstrap -G path/to/new/root packages
```

- Install packages in interactive mode (prompts for confirmation):

```bash
pacstrap -i path/to/new/root packages
```

- Install packages using package files:

```bash
pacstrap -U path/to/new/root path/to/package1 path/to/package2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | genfstab, pacstrap: mention that these are Arch-specific tools (#5795) | 2021-04-20T13:28:54 | [48f2869cf9d2](https://github.com/tldr-pages/tldr/commit/48f2869cf9d225e5b0bb0c879aa70fb23fd5d36f)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacstrap: add page (#5247) | 2021-02-11T17:59:20 | [cb6f74dd28e8](https://github.com/tldr-pages/tldr/commit/cb6f74dd28e8f044e9b782332e36318e7b1aa616)

