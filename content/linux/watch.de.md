---
author: ['Richard Mörbitz']
date: 1634749858
title: "watch"
description: "watch, Führe einen Befehl wiederholt aus und überwache die Ausgabe im Vollbildmodus."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/watch>.

- Überwache die Dateien im aktuellen Verzeichnis:

```bash
watch ls
```

- Überwache verfügbaren Festplatten-Speicherplatz und hebe die Änderungen hervor:

```bash
watch -d df
```

- Überwache "node"-Prozesse und aktualisiere alle 3 Sekunden:

```bash
watch -n 3 "ps aux | grep node"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Richard Mörbitz](mailto:richard.moerbitz@tu-dresden.de) | watch: add German translation (#7073) | 2021-10-20T19:10:58 | [8587c5caa668](https://github.com/tldr-pages/tldr/commit/8587c5caa6682822ac1283b244892da0f166f8d8)

