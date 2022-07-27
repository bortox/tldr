---
author: ['Austin']
date: 1633628068
title: "pacman --database, TLDR Pages"
description: "pacman --database, Mit der Arch Linux Paketdatenbank arbeiten."
categories: "linux"
---
> Verschiedene Attribute von installierten Paketen bearbeiten.

> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Zeige Hilfe an:

```bash
pacman --database --help
```

- Markiere ein Paket als implizit installiert:

```bash
sudo pacman --database --asdeps paketname
```

- Markiere ein Paket als explizit installiert:

```bash
sudo pacman --database --asexplicit paketname
```

- Überprüfe, dass alle Paketabhängigkeiten installiert sind:

```bash
pacman --database --check
```

- Überprüfe in den Repositorien, dass alle angegebenen Abhängigkeiten verfügbar sind:

```bash
pacman --database --check --check
```

- Zeige nur Fehlermeldungen:

```bash
pacman --database --check --quiet
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman-*: add German translation (#6773) | 2021-10-07T19:34:28 | [e0aa976dbee2](https://github.com/tldr-pages/tldr/commit/e0aa976dbee24f9c101cfb787dca043b0fadbefc)

