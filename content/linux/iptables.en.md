---
author: ['Ilya Tribusean', 'Richard Mörbitz', 'Agniva De Sarker', 'slash3b', 'april j', 'Yassine Imounachen', 'Doh', 'HairyFotr']
date: 1636069004
title: "iptables"
description: "iptables, Program that allows configuration of tables, chains and rules provided by the Linux kernel firewall."
categories: "linux"
---
> More information: <https://www.netfilter.org/projects/iptables/>.

- View chains, rules, and packet/byte counters for the filter table:

```bash
sudo iptables -vnL
```

- Set chain policy rule:

```bash
sudo iptables -P chain rule
```

- Append rule to chain policy for IP:

```bash
sudo iptables -A chain -s ip -j rule
```

- Append rule to chain policy for IP considering protocol and port:

```bash
sudo iptables -A chain -s ip -p protocol --dport port -j rule
```

- Add a NAT rule to translate all traffic from the `192.168.0.0/24` subnet to the host's public IP:

```bash
sudo iptables -t nat -A POSTROUTING -s 192.168.0.0/24 -j MASQUERADE
```

- Delete chain rule:

```bash
sudo iptables -D chain rule_line_number
```

- Save iptables configuration of a given table to a file:

```bash
sudo iptables-save -t tablename > path/to/iptables_file
```

- Restore iptables configuration from a file:

```bash
sudo iptables-restore < path/to/iptables_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Richard Mörbitz](mailto:richard.moerbitz@tu-dresden.de) | iptables, nft: add masquerade example (#6979) | 2021-11-05T00:36:44 | [15c9047cb8f4](https://github.com/tldr-pages/tldr/commit/15c9047cb8f47813d4d71ca36c4445d767d9230b)
[Doh](mailto:mydohsimpson@gmail.com) | iptables: fix example description and add link (#4922) | 2020-11-01T20:18:01 | [315a6035c2ed](https://github.com/tldr-pages/tldr/commit/315a6035c2eddb9a023bd16673a5f26905a1de1f)
[april j](mailto:AprilElizabeth@users.noreply.github.com) | iptables: clarify usage and add additional common options (#2208) | 2018-08-12T18:23:48 | [827eb62cb34b](https://github.com/tldr-pages/tldr/commit/827eb62cb34b13140cc8fb94b01874dede1f4965)
[Yassine Imounachen](mailto:yassinei@protonmail.com) | fix capitalisation of option "-p" with small "p" is for protocol | 2017-12-11T18:50:53 | [ad8b796c98f8](https://github.com/tldr-pages/tldr/commit/ad8b796c98f8950308c31b558385cafcf038202e)
[HairyFotr](mailto:hairyfotr@gmail.com) | Fix a few typos | 2017-07-23T16:22:44 | [e0ccb7147a25](https://github.com/tldr-pages/tldr/commit/e0ccb7147a25b5d738e3991f399f87e45f3a4140)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Apply the 'path/to/item' convention uniformly (#947) | 2016-07-13T10:53:22 | [fa8b2d8f92ab](https://github.com/tldr-pages/tldr/commit/fa8b2d8f92abfcbea46036b8a30c129ac53abdcb)
[Ilya Tribusean](mailto:slash3b@gmail.com) | expr, bzip2: add page. iptables: fix typo (#827) | 2016-04-21T14:44:40 | [b3fb312afc6b](https://github.com/tldr-pages/tldr/commit/b3fb312afc6bf1aea92801e6bab7e4900101ac8f)
[slash3b](mailto:slash3b@gmail.com) | iptables: add page | 2016-03-07T08:11:38 | [0fb8ae2285d4](https://github.com/tldr-pages/tldr/commit/0fb8ae2285d414d3ac42377501d67e1654684a7e)

