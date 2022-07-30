---
author: ['Waldir Pimenta', 'Stig124', 'Agniva De Sarker', 'Lucas Gabriel Schneider', 'zlbabe', 'Jacek Wielemborek']
date: 1625841955
title: "cryptsetup"
description: "cryptsetup, Manage plain dm-crypt and LUKS (Linux Unified Key Setup) encrypted volumes."
categories: "linux"
---
> More information: <https://gitlab.com/cryptsetup/cryptsetup/>.

- Initialize a LUKS volume (overwrites all data on the partition):

```bash
cryptsetup luksFormat /dev/sda1
```

- Open a LUKS volume and create a decrypted mapping at `/dev/mapper/{{target}}`:

```bash
cryptsetup luksOpen /dev/sda1 target
```

- Remove an existing mapping:

```bash
cryptsetup luksClose target
```

- Change the LUKS volume's passphrase:

```bash
cryptsetup luksChangeKey /dev/sda1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[zlbabe](mailto:31076777+zlbabe@users.noreply.github.com) | cryptsetup: add luksChangeKey example (#2146) | 2018-06-18T14:08:59 | [9cd177e31da8](https://github.com/tldr-pages/tldr/commit/9cd177e31da8b4040ddf5d1266fc4d85ef591ecb)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | add space before opening parenthesis | 2016-07-14T12:57:44 | [b25bf872407b](https://github.com/tldr-pages/tldr/commit/b25bf872407b6b2097afad7c263c6217c37aaa22)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cryptsetup: simplify page (#953) - Cited actual examples rather than placeholder text - Added the 'close' command | 2016-07-14T12:57:07 | [4b06c127134e](https://github.com/tldr-pages/tldr/commit/4b06c127134e9f2483cc51cf4e8dfc0bfa303514)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Apply the 'path/to/item' convention uniformly (#947) | 2016-07-13T10:53:22 | [fa8b2d8f92ab](https://github.com/tldr-pages/tldr/commit/fa8b2d8f92abfcbea46036b8a30c129ac53abdcb)
[Jacek Wielemborek](mailto:d33tah@gmail.com) | Add cryptsetup.md. | 2016-06-21T12:49:15 | [85eae95f2f5a](https://github.com/tldr-pages/tldr/commit/85eae95f2f5ac3b804aed08a26e8fe666ab258bc)

