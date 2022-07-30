---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "aplay"
description: "aplay, Command-line Musik Player für den ALSA Soundkarten-Treiber."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/aplay>.

- Spiele eine bestimmte Datei (Abtastrate, Bittiefe, etc. werden automatisch für das Dateiformat erkannt):

```bash
aplay pfad/zu/datei
```

- Spiele die ersten 10 Sekunden einer bestimmten Datei mit 2500 Hz:

```bash
aplay --duration=10 --rate=2500 pfad/zu/datei
```

- Spiele die rohe Datei mit 22050 Hz, mono, 8-bit, als Mu-Lw `.au` Datei:

```bash
aplay --channels=1 --file-type raw --rate=22050 --format=mu_law pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

