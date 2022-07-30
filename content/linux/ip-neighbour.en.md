---
author: ['Raizo62', 'Patrice Denis']
date: 1649594825
title: "ip neighbour"
description: "ip neighbour, Neighbour/ARP tables management IP subcommand."
categories: "linux"
---
> More information: <https://manned.org/ip-neighbour.8>.

- Display the neighbour/ARP table entries:

```bash
ip neighbour
```

- Remove entries in the neighbour table on device `eth0`:

```bash
sudo ip neighbour flush dev eth0
```

- Perform a neighbour lookup and return a neighbour entry:

```bash
ip neighbour get lookup_ip dev eth0
```

- Add or delete an ARP entry for the neighbour IP address to `eth0`:

```bash
sudo ip neighbour add|del ip_address lladdr mac_address dev eth0 nud reachable
```

- Change or replace an ARP entry for the neighbour IP address to `eth0`:

```bash
sudo ip neighbour change|replace ip_address lladdr new_mac_address dev eth0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raizo62](mailto:silicium62-github@yahoo.fr) | ip-neighbour.md : title : the command is "ip" and not "ip-neighbour" (#7973) the syntaxof title is now consistent with the others commands | 2022-04-10T14:47:05 | [119c84205ea4](https://github.com/tldr-pages/tldr/commit/119c84205ea469d0ee438fed30a79cf47bb3012d)
[Patrice Denis](mailto:patrice.denis@gmail.com) | ip-neighbour: add page (#5697) | 2021-04-08T15:04:30 | [ce4846141a09](https://github.com/tldr-pages/tldr/commit/ce4846141a0950fb05d467dd6849a311574c06e0)

