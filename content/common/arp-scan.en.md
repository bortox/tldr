---
author: ['gkah']
date: 1631104326
title: "arp-scan"
description: "arp-scan, Send ARP packets to hosts (specified as IP addresses or hostnames) to scan the local network."
categories: "common"
---
> More information: <https://github.com/royhills/arp-scan>.

- Scan the current local network:

```bash
arp-scan --localnet
```

- Scan an IP network with a custom bitmask:

```bash
arp-scan 192.168.1.1/24
```

- Scan an IP network within a custom range:

```bash
arp-scan 127.0.0.0-127.0.0.31
```

- Scan an IP network with a custom net mask:

```bash
arp-scan 10.0.0.0:255.255.255.0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[gkah](mailto:47049232+Fivro@users.noreply.github.com) | arp-scan: move to common platform (#6395) | 2021-09-08T14:32:06 | [ef69c60c84c8](https://github.com/tldr-pages/tldr/commit/ef69c60c84c83ade68917e65c83476ab6c01ac9d)

