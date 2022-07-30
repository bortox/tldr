---
author: ['git-em', 'Axel Navarro', 'Lukáš Zapletal', 'CleanMachine1', 'Seth Falco', 'marchersimon']
date: 1659183837
title: "nmcli connection"
description: "nmcli connection, Connection management with NetworkManager."
categories: "linux"
---
> This subcommand can also be called with `nmcli c`.

> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- List all NetworkManager connections (shows name, UUID, type and device):

```bash
nmcli connection
```

- Activate a connection by specifying a UUID:

```bash
nmcli connection up uuid uuid
```

- Deactivate a connection:

```bash
nmcli connection down uuid uuid
```

- Create an auto-configured dual stack connection:

```bash
nmcli connection add ifname interface_name type ethernet ipv4.method auto ipv6.method auto
```

- Create a static IPv6-only connection:

```bash
nmcli connection add ifname interface_name type ethernet ip6 2001:db8::2/64 gw6 2001:db8::1 ipv6.dns 2001:db8::1 ipv4.method ignore
```

- Create a static IPv4-only connection:

```bash
nmcli connection add ifname interface_name type ethernet ip4 10.0.0.7/8 gw4 10.0.0.1 ipv4.dns 10.0.0.1 ipv6.method ignore
```

- Create a VPN connection using OpenVPN from a OVPN file:

```bash
nmcli connection import type openvpn file path/to/vpn_config.ovpn
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | nmcli-general, nmcli-networking: add page (#8264) * nmcli-general: add page * nmcli-networking: add page | 2022-07-30T14:23:57 | [236c68f8a851](https://github.com/tldr-pages/tldr/commit/236c68f8a8518255b7ca43f17ebe6390430cf853)
[git-em](mailto:56173216+git-em@users.noreply.github.com) | linux/*: replace man.archlinux.com link (#7861) * linux/*: replace man.archlinux.com Does not replace links of pages directly [...] | 2022-03-09T05:31:08 | [8628cba2ebf0](https://github.com/tldr-pages/tldr/commit/8628cba2ebf0939f9aec27530c42351215334eeb)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | nmcli-connection: add import VPN example (#6185) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-07-01T04:27:27 | [13840352d144](https://github.com/tldr-pages/tldr/commit/13840352d144f96aec4db9064b07a53a436daf14)
[Axel Navarro](mailto:navarroaxel@gmail.com) | nmcli: add more information link (#5198) | 2021-01-30T22:05:59 | [23d7996775e1](https://github.com/tldr-pages/tldr/commit/23d7996775e12580a5af45034372cc86c055bf24)
[Lukáš Zapletal](mailto:lzap@redhat.com) | nmcli: add more server examples (#3816) | 2020-03-06T18:10:05 | [e54c56236138](https://github.com/tldr-pages/tldr/commit/e54c562361387aac7856baf59111961c3c0e2999)

