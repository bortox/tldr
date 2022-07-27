---
author: ['Austin']
date: 1634435551
title: "yay, TLDR Pages"
description: "yay, Yet Another Yogurt: Ein Programm für Arch Linux um Pakete vom Arch User Repository zu installieren."
categories: "linux"
---
> Siehe auch `pacman`.

> Weitere Informationen: <https://github.com/Jguer/yay>.

- Suche und installiere Pakete von den Repositorys und dem AUR interaktiv:

```bash
yay paketname|suchbegriff
```

- Synchronisiere und aktualisiere alle Pakete von den Repositorys und dem AUR:

```bash
yay
```

- Synchronisiere und aktualisiere nur AUR-Pakete:

```bash
yay -Sua
```

- Installiere ein neues Paket von den Repositorys und dem AUR:

```bash
yay -S paketname
```

- Entferne ein Paket sowie alle Abhängigkeiten und Konfigurationsdateien:

```bash
yay -Rns paketname
```

- Suche in der Paketdatenbank nach einem Schlüsselwort in den Repositorys und dem AUR:

```bash
yay -Ss schlüsselwort
```

- Entferne verwaiste Pakete (als Abhängigkeit installiert, aber von keinem Paket benötigt):

```bash
yay -Yc
```

- Zeige Statistiken für installierte Pakete sowie die Gesundheit des Systems an:

```bash
yay -Ps
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | yay: add German translation (#7018) | 2021-10-17T03:52:31 | [54b16becc07f](https://github.com/tldr-pages/tldr/commit/54b16becc07fbc9d9b52aa8febc164d9eb815aea)

