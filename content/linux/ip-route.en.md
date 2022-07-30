---
author: ['Patrice Denis']
date: 1618082267
title: "ip route"
description: "ip route, IP Routing table management subcommand."
categories: "linux"
---
> More information: <https://manned.org/ip-route>.

- Display the routing table:

```bash
ip route show|list
```

- Add a default route using gateway forwarding:

```bash
sudo ip route add default via gateway_ip
```

- Add a default route using `eth0`:

```bash
sudo ip route add default dev eth0
```

- Add a static route:

```bash
sudo ip route add destination_ip via gateway_ip dev eth0
```

- Delete a static route:

```bash
sudo ip route del destination_ip dev eth0
```

- Change or replace a static route:

```bash
sudo ip route change|replace destination_ip via gateway_ip dev eth0
```

- Show which route will be used by the kernel to reach an IP address:

```bash
ip route get destination_ip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | ip-route: add page (#5696) | 2021-04-10T21:17:47 | [7d38f9d22848](https://github.com/tldr-pages/tldr/commit/7d38f9d22848468ebd5dd784e1cbe924bf893e73)

