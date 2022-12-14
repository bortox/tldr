---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "arecord"
description: "arecord, Sound Recorder für den ALSA Soundkarten Treiber."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/arecord>.

- Nehme einen Schnipsel in "CD" Qualität auf (beende die Aufnahme mit CTRL-C):

```bash
arecord -vv --format=cd pfad/zur/datei.wav
```

- Nehme einen Schnipsel in "CD" Qualität auf mit einer festen Länge von 10 Sekunden:

```bash
arecord -vv --format=cd --duration=10 pfad/zur/datei.wav
```

- Nehme einen Schnipsel auf und speichere es als MP3 (beende die Aufnahme mit CTRL-C):

```bash
arecord -vv --format=cd --file-type raw | lame -r - path/to/file.mp3
```

- Liste alle Soundkarten und digitalen Ausgabe Geräte:

```bash
arecord --list-devices
```

- Benutze das interaktive Interface (z.B. Space oder Enter für Play oder Pause):

```bash
arecord --interactive
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

