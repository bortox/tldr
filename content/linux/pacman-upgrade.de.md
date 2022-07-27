---
author: ['Austin']
date: 1633628068
title: "pacman --upgrade, TLDR Pages"
description: "pacman --upgrade, Arch Linux Paketverwaltungs-Werkzeug."
categories: "linux"
---
> Weitere Informationen: <https://man.archlinux.org/man/pacman.8>.

- Zeige Hilfe an:

```bash
pacman --upgrade --help
```

- Installiere ein oder mehrere Pakete von Dateien:

```bash
sudo pacman --upgrade pfad/zu/paket1.pkg.tar.zst pfad/zu/paket2.pkg.tar.zst
```

- Installiere ein Paket ohne Bestätigungsaufforderung:

```bash
sudo pacman --upgrade --noconfirm pfad/zu/paket.pkg.tar.zst
```

- Überschreibe widersprüchliche Dateien während einer Paketinstallation:

```bash
sudo pacman --upgrade --overwrite pfad/zu/datei pfad/zu/paket.pkg.tar.zst
```

- Installiere ein Paket und überspringe die Überprüfung von Abhängigkeitsversionen:

```bash
sudo pacman --upgrade --nodeps pfad/zu/paket.pkg.tar.zst
```

- Liste Pakete auf, welche betroffen sein würden (installiert keine Pakete):

```bash
pacman --query --print pfad/zu/paket.pkg.tar.zst
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | pacman-*: add German translation (#6773) | 2021-10-07T19:34:28 | [e0aa976dbee2](https://github.com/tldr-pages/tldr/commit/e0aa976dbee24f9c101cfb787dca043b0fadbefc)

