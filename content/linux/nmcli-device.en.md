---
author: ['Lukáš Zapletal', 'Axel Navarro', 'David Auer', 'git-em']
date: 1646800268
title: "nmcli device, TLDR Pages"
description: "nmcli device, Hardware device management with NetworkManager."
categories: "linux"
---
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Print the statuses of all network interfaces:

```bash
nmcli device status
```

- Print the available Wi-Fi access points:

```bash
nmcli device wifi
```

- Connect to the Wi-Fi network with a specified name and password:

```bash
nmcli device wifi connect ssid password password
```

- Print password and QR code for the current Wi-Fi network:

```bash
nmcli device wifi show-password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | linux/*: replace man.archlinux.com link (#7861) * linux/*: replace man.archlinux.com Does not replace links of pages directly [...] | 2022-03-09T05:31:08 | [8628cba2ebf0](https://github.com/tldr-pages/tldr/commit/8628cba2ebf0939f9aec27530c42351215334eeb)
[Axel Navarro](mailto:navarroaxel@gmail.com) | nmcli: add more information link (#5198) | 2021-01-30T22:05:59 | [23d7996775e1](https://github.com/tldr-pages/tldr/commit/23d7996775e12580a5af45034372cc86c055bf24)
[David Auer](mailto:dreua@posteo.de) | nmcli-device: add wifi show-password example (#5191) | 2021-01-28T11:08:26 | [09e78d4bc2ee](https://github.com/tldr-pages/tldr/commit/09e78d4bc2ee41928f221f1510788d6caed34bdf)
[Lukáš Zapletal](mailto:lzap@redhat.com) | nmcli: add more server examples (#3816) | 2020-03-06T18:10:05 | [e54c56236138](https://github.com/tldr-pages/tldr/commit/e54c562361387aac7856baf59111961c3c0e2999)

