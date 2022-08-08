---
author: ['kai']
date: 1659914490
title: "grub-bios-setup"
description: "grub-bios-setup, Set up a device to use GRUB with a BIOS configuration."
categories: "linux"
---
> You should use `grub-install` instead of `grub-bios-setup` in most cases.

> More information: <https://manned.org/grub-bios-setup.8>.

- Set up a device to boot with GRUB:

```bash
grub-bios-setup /dev/sdX
```

- Install even if problems are detected:

```bash
grub-bios-setup --force /dev/sdX
```

- Install GRUB in a specific directory:

```bash
grub-bios-setup --directory=/boot/grub /dev/sdX
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[kai](mailto:gmdezreal@gmail.com) | grub-bios-setup: add page (#8315) * grub-bios-setup: add page * grub-bios-setup: use better wording for example descriptions Co- [...] | 2022-08-08T01:21:30 | [a703584eecb5](https://github.com/tldr-pages/tldr/commit/a703584eecb5b00f674ef4c6a241000065a5686c)

