---
author: ['Managor']
date: 1613757576
title: "wol, TLDR Pages"
description: "wol, Client for sending Wake-on-LAN magic packets."
categories: "linux"
---
> More information: <https://sourceforge.net/projects/wake-on-lan/>.

- Send a WoL packet to a device:

```bash
wol mac_address
```

- Send a WoL packet to a device in another subnet based on its IP:

```bash
wol --ipaddr=ip_address mac_address
```

- Send a WoL packet to a device in another subnet based on its hostname:

```bash
wol --host=hostname mac_address
```

- Send a WoL packet to a specific port on a host:

```bash
wol --port=port_number mac_address
```

- Read hardware addresses, IP addresses/hostnames, optional ports and SecureON passwords from a file:

```bash
wol --file=path/to/file
```

- Turn on verbose output:

```bash
wol --verbose mac_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Managor](mailto:42655600+Managor@users.noreply.github.com) | wol: add page (#5280) | 2021-02-19T18:59:36 | [92a974ac0685](https://github.com/tldr-pages/tldr/commit/92a974ac0685c8d4ac3452bfa0ab13c1b5c49ab6)

