---
author: ['krishchopra02', 'Richard Mörbitz', 'Rowan Freeman']
date: 1636069004
title: "nft, TLDR Pages"
description: "nft, Allows configuration of tables, chains and rules provided by the Linux kernel firewall."
categories: "linux"
---
> Nftables replaces iptables.

> More information: <https://wiki.nftables.org/wiki-nftables/index.php/Main_Page>.

- View current configuration:

```bash
sudo nft list ruleset
```

- Add a new table with family "inet" and table "filter":

```bash
sudo nft add table inet filter
```

- Add a new chain to accept all inbound traffic:

```bash
sudo nft add chain inet filter input \{ type filter hook input priority 0 \; policy accept \}
```

- Add a new rule to accept several TCP ports:

```bash
sudo nft add rule inet filter input tcp dport \{ telnet, ssh, http, https \} accept
```

- Add a NAT rule to translate all traffic from the `192.168.0.0/24` subnet to the host's public IP:

```bash
sudo nft add rule nat postrouting ip saddr 192.168.0.0/24 masquerade
```

- Show rule handles:

```bash
sudo nft --handle --numeric list chain family table chain
```

- Delete a rule:

```bash
sudo nft delete rule inet filter input handle 3
```

- Save current configuration:

```bash
sudo nft list ruleset > /etc/nftables.conf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Richard Mörbitz](mailto:richard.moerbitz@tu-dresden.de) | iptables, nft: add masquerade example (#6979) | 2021-11-05T00:36:44 | [15c9047cb8f4](https://github.com/tldr-pages/tldr/commit/15c9047cb8f47813d4d71ca36c4445d767d9230b)
[krishchopra02](mailto:77331421+krishchopra02@users.noreply.github.com) | nft: add link (#7027) | 2021-10-18T14:06:10 | [36f62ebbe0af](https://github.com/tldr-pages/tldr/commit/36f62ebbe0af1970b0fa479064b72abf80690902)
[Rowan Freeman](mailto:rowanfreeman@users.noreply.github.com) | nft: add page (#1932) | 2018-02-03T11:30:37 | [41e691a12b8a](https://github.com/tldr-pages/tldr/commit/41e691a12b8aea74945595b09092eb3e2bd60f72)

