---
author: ['Austin']
date: 1633628068
title: "pacman --remove"
description: "pacman --remove, Arch Linux Paketverwaltungs-Werkzeug."
categories: "linux"
---
> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Zeige Hilfe für diesen Unterbefehl an:

```bash
pacman --remove --help
```

- Entferne ein Paket und dessen Abhängigkeiten:

```bash
sudo pacman --remove --recursive paketname
```

- Entferne ein Paket sowie alle Abhängigkeiten und Konfigurationsdateien:

```bash
sudo pacman --remove --recursive --nosave paketname
```

- Entferne ein Paket ohne Bestätigungsaufforderung:

```bash
sudo pacman --remove --noconfirm paketname
```

- Entferne verwaiste Pakete (Pakete welche als Abhängigkeit installiert wurden, aber von keinem Paket benötigt werden):

```bash
sudo pacman --remove --recursive --nosave $(pacman --query --unrequired --deps --quiet)
```

- Entferne ein Paket und alle Pakete die davon abhängig sind:

```bash
sudo pacman --remove --cascade paketname
```

- Liste Pakete auf, welche betroffen sein würden (entfernt keine Pakete):

```bash
pacman --remove --print paketname
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman-*: add German translation (#6773) | 2021-10-07T19:34:28 | [e0aa976dbee2](https://github.com/tldr-pages/tldr/commit/e0aa976dbee24f9c101cfb787dca043b0fadbefc)

