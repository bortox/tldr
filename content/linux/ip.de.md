---
author: ['MarkusS', 'marchersimon', 'Daniel']
date: 1634914980
title: "ip, TLDR Pages"
description: "ip, Zeige und manipuliere routing, Geräte, Policy routing und Tunnel."
categories: "linux"
---
> Weitere Informationen: <https://www.man7.org/linux/man-pages/man8/ip.8.html>.

- Zeige Interfaces mit detaillierten Informationen:

```bash
ip address
```

- Zeige Interfaces mit kurzen Netzwerkinformationen:

```bash
ip -brief address
```

- Zeige Interfaces mit kurzen link layer Informationen:

```bash
ip -brief link
```

- Zeige die Routing Tabelle:

```bash
ip route
```

- Zeige Nachbarn (ARP Tabelle):

```bash
ip neighbour
```

- Schalte ein bestimmtes Interface ein oder aus:

```bash
ip link set interface up|down
```

- Entferne oder füge eine IP zu einem Interface hinzu:

```bash
ip addr add/del ip/mask dev interface
```

- Füge eine Standard Route hinzu:

```bash
ip route add default via ip dev interface
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[MarkusS](mailto:markusscoding@outlook.com) | alpine, apt*, dnf, ip*: add German translation (#4707) | 2020-10-19T18:41:28 | [6e04e6dfc57e](https://github.com/tldr-pages/tldr/commit/6e04e6dfc57e323fed7b4ab2e5f46358463b2008)

