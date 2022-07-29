---
author: ['Nicolas Hansse']
date: 1659035463
title: "arp-scan, TLDR Pages"
description: "arp-scan, Envoie des paquets ARP à des hôtes (spécifié via des adresses IP ou des noms de domaines) pour scanner le réseau local."
categories: "common"
---
> Plus d'informations : <https://github.com/royhills/arp-scan>.

- Scanne le réseau local actuel :

```bash
arp-scan --localnet
```

- Scanne un réseau IP pour un masque de bits donné :

```bash
arp-scan 192.168.1.1/24
```

- Scanne un réseau IP dans une plage IP :

```bash
arp-scan 127.0.0.0-127.0.0.31
```

- Scanne un réseau IP pour un masque de sous-réseaux donné :

```bash
arp-scan 10.0.0.0:255.255.255.0
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | arp, arp-scan: add French translation (#8261) | 2022-07-28T21:11:03 | [4b3b3002de07](https://github.com/tldr-pages/tldr/commit/4b3b3002de07dd155d1df55f46e36eca1007d5f3)

