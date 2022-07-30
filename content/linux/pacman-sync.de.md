---
author: ['Austin']
date: 1633628068
title: "pacman --sync"
description: "pacman --sync, Arch Linux Paketverwaltungs-Werkzeug."
categories: "linux"
---
> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Installiere ein neues Paket:

```bash
sudo pacman --sync paketname
```

- Synchronisiere und aktualisiere alle Pakete (füge `--downloadonly` hinzu um die Pakete nur herunterzuladen und nicht zu aktualisieren):

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Aktualisiere alle Pakete und installiere ein neues ohne Bestätigungsaufforderung:

```bash
sudo pacman --sync --refresh --sysupgrade --noconfirm paketname
```

- Suche in der Paketdatenbank mit einem regulärem Ausdruck oder Schlüsselwort:

```bash
pacman --sync --search "suchmuster"
```

- Zeige Informationen über ein Paket an:

```bash
pacman --sync --info paketname
```

- Überschreibe widersprüchliche Dateien während einer Paketaktualisierung:

```bash
sudo pacman --sync --refresh --sysupgrade --overwrite pfad/zur/datei
```

- Synchronisiere und aktualisiere alle Pakete, ignoriere aber ein bestimmtes Paket (kann mehr als einmal angegeben werden):

```bash
sudo pacman --sync --refresh --sysupgrade --ignore paketname
```

- Entferne nicht installierte Pakete und ungenutzte Repositorys vom Cache (nutze zwei `--clean` Operationen um alle Pakete aufzuräumen):

```bash
sudo pacman --sync --clean
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman-*: add German translation (#6773) | 2021-10-07T19:34:28 | [e0aa976dbee2](https://github.com/tldr-pages/tldr/commit/e0aa976dbee24f9c101cfb787dca043b0fadbefc)

