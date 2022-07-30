---
author: ['Hayden Schiff', 'pxgamer']
date: 1560056064
title: "dhcpwn"
description: "dhcpwn, Test DHCP IP exhaustion attacks and sniff local DHCP traffic."
categories: "common"
---
> More information: <https://github.com/mschwager/dhcpwn>.

- Flood the network with IP requests:

```bash
dhcpwn --interface network_interface flood --count number_of_requests
```

- Sniff local DHCP traffic:

```bash
dhcpwn --interface network_interface sniff
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | dhcpwn: add link to homepage | 2019-06-09T06:54:24 | [8ea784d9154f](https://github.com/tldr-pages/tldr/commit/8ea784d9154f6feab40c8148270a8e739a50dda6)
[Hayden Schiff](mailto:oxguy3@gmail.com) | dhcpwn: add page | 2016-01-28T21:25:12 | [02532061ebdf](https://github.com/tldr-pages/tldr/commit/02532061ebdfd6bf6769c0e124cfa0b0494434ae)

