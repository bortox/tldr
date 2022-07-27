---
author: ['Marco Bonelli', 'Starbeamrainbowlabs']
date: 1559564381
title: "pivpn, TLDR Pages"
description: "pivpn, Easy security-hardened OpenVPN setup and manager."
categories: "linux"
---
> Originally designed for the Raspberry Pi, but works on other Linux devices too.

> More information: <http://www.pivpn.io/>.

- Add a new client device:

```bash
sudo pivpn add
```

- List all client devices:

```bash
sudo pivpn list
```

- List currently connected devices and their statistics:

```bash
sudo pivpn clients
```

- Revoke a previously authenticated device:

```bash
sudo pivpn revoke
```

- Uninstall PiVPN:

```bash
sudo pivpn uninstall
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | pivpn: add page (#2671) | 2019-01-29T07:48:01 | [46b143e14e99](https://github.com/tldr-pages/tldr/commit/46b143e14e990ce7e1b060e9124596d7113a85ac)

