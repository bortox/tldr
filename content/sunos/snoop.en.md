---
author: ['Alan Landucci-Ruiz', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "snoop"
description: "snoop, Network packet sniffer."
categories: "sunos"
---
> SunOS equivalent of tcpdump.

> More information: <https://www.unix.com/man-page/sunos/1m/snoop>.

- Capture packets on a specific network interface:

```bash
snoop -d e1000g0
```

- Save captured packets in a file instead of displaying them:

```bash
snoop -o filename
```

- Display verbose protocol layer summary of packets from a file:

```bash
snoop -V -i filename
```

- Capture network packets that come from a hostname and go to a given port:

```bash
snoop to port port from host hostname
```

- Capture and show a hex-dump of network packets exchanged between two IP addresses:

```bash
snoop -x0 -p4 ip_address_1 ip_address_2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sunos/*: add more information link (#5649) | 2021-03-31T13:09:14 | [d12aac42e8d5](https://github.com/tldr-pages/tldr/commit/d12aac42e8d5a4f35d0766c0cd5127ab76b6dc76)
[Alan Landucci-Ruiz](mailto:MClaw666@yahoo.com) | snoop: add page (#3457) | 2019-12-09T19:33:38 | [06eac7761409](https://github.com/tldr-pages/tldr/commit/06eac77614092127dd20d95d9835225115793919)

