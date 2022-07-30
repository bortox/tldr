---
author: ['Austin']
date: 1633628068
title: "pacman --query"
description: "pacman --query, Arch Linux Paketverwaltungs-Werkzeug."
categories: "linux"
---
> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Liste alle installierten Pakete und dessen Versionen auf:

```bash
pacman --query
```

- Liste alle ausdrücklich installierten Pakete und dessen Versionen auf:

```bash
pacman --query --explicit
```

- Finde heraus welches Paket eine Datei besitzt:

```bash
pacman --query --owns dateiname
```

- Zeige Informationen über ein installiertes Paket an:

```bash
pacman --query --info paketname
```

- Liste alle Dateien auf welche einem Paket gehören:

```bash
pacman --query --list paketname
```

- Liste verwaiste Pakete auf (Pakete welche als Abhängigkeit installiert wurden, aber von keinem Paket benötigt werden):

```bash
pacman --query --unrequired --deps --quiet
```

- Liste installierte Pakete auf welche nicht in den Repositorien gefunden werden können:

```bash
pacman --query --foreign
```

- Liste veraltete Pakete auf:

```bash
pacman --query --upgrades
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman-*: add German translation (#6773) | 2021-10-07T19:34:28 | [e0aa976dbee2](https://github.com/tldr-pages/tldr/commit/e0aa976dbee24f9c101cfb787dca043b0fadbefc)

