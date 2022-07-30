---
author: ['Antoine Amara']
date: 1570272353
title: "hping"
description: "hping, Command-line oriented TCP/IP packet assembler and analyzer."
categories: "common"
---
> Inspired by the `ping` command.

> More information: <http://www.hping.org>.

- Ping localhost over TCP:

```bash
hping3 localhost
```

- Ping an IP address over TCP on a specific port:

```bash
hping3 -p 80 -S 192.168.1.1
```

- Ping an IP address over UDP on port 80:

```bash
hping3 --udp -p 80 -S 192.168.1.1
```

- Scan a set of TCP ports on a specific IP address:

```bash
hping3 --scan 80,3000,9000 -S 192.168.1.1
```

- Perform a charge test on port 80:

```bash
hping3 --flood -p 80 -S 192.168.1.1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Antoine Amara](mailto:amara.antoine@gmail.com) | hping: add new page (#3305) | 2019-10-05T12:45:53 | [c2db2b45b7cb](https://github.com/tldr-pages/tldr/commit/c2db2b45b7cb876c05420c679e0486450a758ada)

