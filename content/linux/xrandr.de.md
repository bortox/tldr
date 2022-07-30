---
author: ['Spicyyboi', 'marchersimon']
date: 1636390112
title: "xrandr"
description: "xrandr, Setzt die Auflösung, Orientierung und/oder Reflektion eines Bildschirmausgangs."
categories: "linux"
---
> Weitere Informationen: <https://www.x.org/releases/current/doc/man/man1/xrandr.1.xhtml>.

- Zeige den momentanen Systemzustand an (erkannte Bildschirme, Auflösungen, ...):

```bash
xrandr --query
```

- Deaktiviere nicht mehr verbundene Ausgangsgeräte und aktiviere verbundene Ausgänge mit Standardeinstellungen:

```bash
xrandr --auto
```

- Ändere die Auflösung und Bildfrequenz von DisplayPort 1 zu 1920x1080, 60Hz:

```bash
xrandr --output DP1 --mode 1920x1080 --rate 60
```

- Setze die Auflösung von HDMI auf 1280x1024 und platziere HDMI1 rechts von DP1:

```bash
xrandr --output HDMI2 --mode 1280x1024 --right-of DP1
```

- Deaktiviere den Ausgang von VGA1:

```bash
xrandr --output VGA1 --off
```

- Setze die Bildschirmhelligkeit von LVDS1 auf 50%:

```bash
xrandr --output LVDS1 --brightness 0.5
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xrandr: remove duplicate example (#7389) | 2021-11-08T17:48:32 | [8793761d559f](https://github.com/tldr-pages/tldr/commit/8793761d559fedf3cb9f1a58705cbd044cba4cde)
[Spicyyboi](mailto:34308782+spicyyboi@users.noreply.github.com) | xrandr: add German translation (#7254) | 2021-11-01T15:20:28 | [f56316e2763d](https://github.com/tldr-pages/tldr/commit/f56316e2763d5b276e6df87a584bf98645872a3e)

