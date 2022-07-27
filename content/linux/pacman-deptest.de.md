---
author: ['Austin']
date: 1633628068
title: "pacman --deptest, TLDR Pages"
description: "pacman --deptest, Überprüfe alle angegebenen Abhängigkeiten und gib eine Liste von Abhängigkeiten zurück, welche auf dem System nicht erfüllt sind."
categories: "linux"
---
> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Zeige Paketnamen von Abhängigkeiten an, welche nicht installiert sind:

```bash
pacman --deptest paketname1 paketname2
```

- Überprüfe ob ein installiertes Paket eine Minimalversion erfüllt:

```bash
pacman --deptest "bash>=5"
```

- Überprüfe ob eine neuere version eines Paketes installiert ist:

```bash
pacman --deptest "bash>5"
```

- Zeige Hilfe an:

```bash
pacman --deptest --help
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman-*: add German translation (#6773) | 2021-10-07T19:34:28 | [e0aa976dbee2](https://github.com/tldr-pages/tldr/commit/e0aa976dbee24f9c101cfb787dca043b0fadbefc)

