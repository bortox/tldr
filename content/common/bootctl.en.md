---
author: ['marchersimon', 'git-em']
date: 1646800137
title: "bootctl, TLDR Pages"
description: "bootctl, Control EFI firmware boot settings and manage boot loader."
categories: "common"
---
> More information: <https://manned.org/bootctl>.

- Show information about the system firmware and the bootloaders:

```bash
sudo bootctl status
```

- Set a flag to boot into the system firmware on the next boot (similar to `sudo systemctl reboot --firmware-setup`):

```bash
sudo bootctl reboot-to-firmware true
```

- Specify the path to the EFI system partition (defaults to `/efi/`, `/boot/` or `/boot/efi`):

```bash
sudo bootctl --esp-path=/path/to/efi_system_partition/
```

- Show all available bootloader entries:

```bash
sudo bootctl list
```

- Install `systemd-boot` into the EFI system partition:

```bash
sudo bootctl install
```

- Remove all installed versions of `systemd-boot` from the EFI system partition:

```bash
sudo bootctl remove
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | common/*: replace man.archlinux.org (#7860) | 2022-03-09T05:28:57 | [a48819f19092](https://github.com/tldr-pages/tldr/commit/a48819f19092a82a1faef1f9f105bc1eb27d2df7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | bootctl: add page (#5418) | 2021-03-12T13:42:13 | [67550155444d](https://github.com/tldr-pages/tldr/commit/67550155444d37b5ed8cd35dd66d9ca7eddc8b23)

