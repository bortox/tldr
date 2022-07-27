---
author: ['bl-ue', 'marchersimon']
date: 1619262596
title: "gplusplus, TLDR Pages"
description: "gplusplus, Kompiliere C++ Quelldateien."
categories: "common"
---
> Teil der GCC (GNU Compiler Collection).

> Weitere Informationen: <https://gcc.gnu.org>.

- Kompiliere eine Quelldatei in eine ausführbare Binärdatei:

```bash
g++ quelldatei.cpp -o output_datei
```

- Zeige (fast) alle Fehler und Warnungen an:

```bash
g++ quelldatei.cpp -Wall -o output_datei
```

- Wähle einen Sprachstandard für das Kompilieren:

```bash
g++ quelldatei.cpp -std=C++98|C++11|C++14|C++17 -o output_datei
```

- Binde Bibliotheken, die sich an einem anderen Pfad als die Quelldatei befinden mit ein:

```bash
g++ quelldatei.cpp -o output_datei -Iheader_pfad -Lbibliotheks_pfad -lbibliotheks_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

