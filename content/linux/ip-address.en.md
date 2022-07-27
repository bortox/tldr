---
author: ['Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1630607629
title: "ip address, TLDR Pages"
description: "ip address, IP Address management subcommand."
categories: "linux"
---
> More information: <https://manned.org/ip-address>.

- List network interfaces and their associated IP addresses:

```bash
ip address
```

- Filter to show only active network interfaces:

```bash
ip address show up
```

- Display information about a specific network interface:

```bash
ip address show dev eth0
```

- Add an IP address to a network interface:

```bash
ip address add ip_address dev eth0
```

- Remove an IP address from a network interface:

```bash
ip address delete ip_address dev eth0
```

- Delete all IP addresses in a given scope from a network interface:

```bash
ip address flush dev eth0 scope global|host|link
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | ip address: use a specific network interface example (#3987) | 2020-04-30T14:50:51 | [5ccd89309bcd](https://github.com/tldr-pages/tldr/commit/5ccd89309bcd80e86941c800a07f54777c6cca1f)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | ip address: add page (#3930) | 2020-03-27T14:37:59 | [a687c64e3ff5](https://github.com/tldr-pages/tldr/commit/a687c64e3ff5e8d2d16c87bb2c637cd76cc409bc)

