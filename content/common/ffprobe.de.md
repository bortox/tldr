---
author: ['marchersimon']
date: 1619262596
title: "ffprobe, TLDR Pages"
description: "ffprobe, Multimedia Stream Analysierer."
categories: "common"
---
> Weitere Informationen: <https://ffmpeg.org/ffprobe.html>.

- Zeige alle verfügbaren Stream-Informationen einer Medien-Datei an:

```bash
ffprobe -v error -show_entries datei.mp4
```

- Zeige Spieldauer an:

```bash
ffprobe -v error -show_entries format=duration -of default=noprint_wrappers=1:nokey=1 datei.mp4
```

- Zeige die Bildfrequenz eines Videos an:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=avg_frame_rate -of default=noprint_wrappers=1:nokey=1 datei.mp4
```

- Zeige die Breite (width) oder Höhe (height) eines Videos an:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=width|height -of default=noprint_wrappers=1:nokey=1 datei.mp4
```

- Zeige die durchschnittliche Bitrate eines Videos an:

```bash
ffprobe -v error -select_streams v:0 -show_entries stream=bit_rate -of default=noprint_wrappers=1:nokey=1 datei.mp4
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

