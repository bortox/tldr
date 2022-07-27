---
author: ['CleanMachine1', 'ciph3rz']
date: 1657497846
title: "hping3, TLDR Pages"
description: "hping3, Advanced ping utility which supports protocols such TCP, UDP, and raw IP."
categories: "common"
---
> Best run with elevated privileges.

> More information: <https://github.com/antirez/hping>.

- Ping a destination with 4 ICMP ping requests:

```bash
hping3 --icmp --count 4 ip_or_hostname
```

- Scan TCP port 80, scanning from the specific local source port 5090:

```bash
hping3 --verbose --syn --destport 80 --baseport 5090 ip_or_hostname
```

- Traceroute using a TCP scan to a specific destination port:

```bash
hping3 --traceroute --verbose --syn --destport 80 ip_or_hostname
```

- Perform a TCP ACK scan to check if a given host is alive:

```bash
hping3 --count 2 --verbose --destport 80 -A ip_or_hostname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | common/*: fix spelling errors | 2022-07-11T02:04:06 | [e4719999325f](https://github.com/tldr-pages/tldr/commit/e4719999325f611503c2ad1dc7bea3e8ac25f557)
[ciph3rz](mailto:46655414+ciph3rz@users.noreply.github.com) | hping3: add page (#7147) | 2021-12-02T02:56:30 | [26ecfa49699d](https://github.com/tldr-pages/tldr/commit/26ecfa49699d548359b89135e77fee1eeb3aa5a8)

