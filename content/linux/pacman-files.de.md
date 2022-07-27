---
author: ['Austin']
date: 1633628068
title: "pacman --files, TLDR Pages"
description: "pacman --files, Arch Linux Paketverwaltungs-Werkzeug."
categories: "linux"
---
> Siehe auch `pkgfile`.

> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Zeige Hilfe an:

```bash
pacman --files --help
```

- Aktualisiere die Paketdatenbank:

```bash
sudo pacman --files --refresh
```

- Finde das Paket, welches eine bestimmte Datei besitzt:

```bash
pacman --files dateiname
```

- Finde das Paket, welches eine bestimmte Datei besitzt, mittels einem regulärem Ausdruck:

```bash
pacman --files --regex 'suchmuster'
```

- Liste nur Paketnamen auf:

```bash
pacman --files --quiet dateiname
```

- Liste die Dateien auf welche einem bestimmten Paket gehören:

```bash
pacman --files --list paketname
```

- Liste nur den absoluten Pfad der Dateien auf:

```bash
pacman --query --list --quiet paketname
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman-*: add German translation (#6773) | 2021-10-07T19:34:28 | [e0aa976dbee2](https://github.com/tldr-pages/tldr/commit/e0aa976dbee24f9c101cfb787dca043b0fadbefc)

