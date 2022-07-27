---
author: ['Raymond Douglas', 'Lucas Gabriel Schneider']
date: 1630607629
title: "ipcalc, TLDR Pages"
description: "ipcalc, Perform simple operations and calculations on IP addresses and networks."
categories: "linux"
---
> More information: <https://manned.org/ipcalc>.

- Show information about an address or network with a given subnet mask:

```bash
ipcalc 1.2.3.4 255.255.255.0
```

- Show information about an address or network in CIDR notation:

```bash
ipcalc 1.2.3.4/24
```

- Show the broadcast address of an address or network:

```bash
ipcalc -b 1.2.3.4/30
```

- Show the network address of provided IP address and netmask:

```bash
ipcalc -n 1.2.3.4/24
```

- Display geographic information about a given IP address:

```bash
ipcalc -g 1.2.3.4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Raymond Douglas](mailto:raymondjdouglas@gmail.com) | ipcalc: update description | 2018-09-04T19:12:18 | [88d0396d08fc](https://github.com/tldr-pages/tldr/commit/88d0396d08fc1a3358d0bd3f50c859e75fdceaf2)
[Raymond Douglas](mailto:raymondjdouglas@gmail.com) | ipcalc: add concrete values | 2018-09-04T19:12:18 | [2332740b8f9d](https://github.com/tldr-pages/tldr/commit/2332740b8f9d3629816a6672ef5e2b97f171cdd7)
[Raymond Douglas](mailto:raymondjdouglas@gmail.com) | ipcalc: clarified descriptions | 2018-09-04T19:12:18 | [2cda19e75be4](https://github.com/tldr-pages/tldr/commit/2cda19e75be4ddcf30af1ba880bcac8c6a6c5f81)
[Raymond Douglas](mailto:raymondjdouglas@gmail.com) | ipcalc: add page | 2018-09-04T19:12:18 | [eba372ca23ee](https://github.com/tldr-pages/tldr/commit/eba372ca23ee35d5475eb79c3fdc995bcd0b677e)

