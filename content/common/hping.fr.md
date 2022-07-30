---
author: ['bl-ue', 'Antoine Amara', 'marchersimon']
date: 1633592259
title: "hping"
description: "hping, Outil en ligne de commande permettant d'assembler ou analyser des paquets TCP/IP."
categories: "common"
---
> Inspirer par la commande `ping`.

> Plus d'informations : <http://www.hping.org>.

- Ping localhost via TCP :

```bash
hping3 localhost
```

- Ping une adresse IP, via TCP, sur un port spécifique :

```bash
hping3 -p 80 -S 192.168.1.1
```

- Ping une adresse IP, via UDP, sur le port 80 :

```bash
hping3 --udp -p 80 -S 192.168.1.1
```

- Scanner un ensemble de ports TCP, sur une adresse IP spécifique :

```bash
hping3 --scan 80,3000,9000 -S 192.168.1.1
```

- Effectuer un test de montée en charge sur le port 80 :

```bash
hping3 --flood -p 80 -S 192.168.1.1
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Antoine Amara](mailto:amara.antoine@gmail.com) | hping: add French translation (#3366) | 2019-10-27T17:43:28 | [5195e9c5c985](https://github.com/tldr-pages/tldr/commit/5195e9c5c985ec71c56af03082dbea0fdca90dac)

