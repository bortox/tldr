---
author: ['MarkusS', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1630607629
title: "ip address"
description: "ip address, IP Adressen Management Unterbefehl."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/ip-address>.

- Zeige Netzwerk-Interfaces mit ihren Adressen:

```bash
ip address
```

- Zeige nur die aktiven Netzwerk-Interfaces:

```bash
ip address show up
```

- Zeige Informationen über ein bestimmtes Interface:

```bash
ip address show dev eth0
```

- Füge eine Adresse zu einem Interface hinzu:

```bash
ip address add ip_adresse dev eth0
```

- Entferne eine Adresse von einem Interface:

```bash
ip address delete ip_adresse dev eth0
```

- Entfernt alle IP Adressen in einem speziellen Bereich von einem Interface:

```bash
ip address flush dev eth0 scope global|host|link
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[MarkusS](mailto:markusscoding@outlook.com) | alpine, apt*, dnf, ip*: add German translation (#4707) | 2020-10-19T18:41:28 | [6e04e6dfc57e](https://github.com/tldr-pages/tldr/commit/6e04e6dfc57e323fed7b4ab2e5f46358463b2008)

