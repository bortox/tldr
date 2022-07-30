---
author: ['Waldir Pimenta', 'Paweł Sacawa', 'bl-ue', 'CleanMachine1', 'marchersimon']
date: 1652044954
title: "efibootmgr"
description: "efibootmgr, Manipulate the UEFI Boot Manager."
categories: "linux"
---
> More information: <https://manned.org/efibootmgr>.

- List the current settings then bootnums with their name:

```bash
efibootmgr
```

- List the filepaths:

```bash
efibootmgr -v
```

- Add UEFI Shell v2 as a boot option:

```bash
sudo efibootmgr -c -d /dev/sda1 -l \EFI\tools\Shell.efi -L "UEFI Shell"
```

- Change the current boot order:

```bash
sudo efibootmgr -o 0002,0008,0001,0005
```

- Delete a boot option:

```bash
sudo efibootmgr -b 0008 --delete-bootnum
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | efibootmgr: add clarity (#8079) | 2022-05-08T23:22:34 | [7698f52edf86](https://github.com/tldr-pages/tldr/commit/7698f52edf86d589a2c858239fdb1a84535f2c11)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Paweł Sacawa](mailto:psacawa@math.toronto.edu) | efibootmgr: fix misnamed command (#4467) | 2020-10-05T09:18:13 | [cb2bd5938a76](https://github.com/tldr-pages/tldr/commit/cb2bd5938a76c12c847f8537319a052b210bce3b)

