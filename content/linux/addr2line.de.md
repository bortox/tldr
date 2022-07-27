---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "addr2line, TLDR Pages"
description: "addr2line, Konvertiere Adressen von Binärdateien in Dateinamen und Zeilennummern."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/addr2line>.

- Zeige den Dateinamen und die Zeilennummer des Quellcodes von einer Befehlssadresse einer ausführbaren Datei an:

```bash
addr2line --exe=pfad/zur/ausführbaren_datei adresse
```

- Zeige den Funktionsnamen, Dateinamen und Zeilennummer an:

```bash
addr2line --exe=pfad/zum/executable --functions adresse
```

- Entmangele den Funktionsnamen für C++ Code:

```bash
addr2line --exe=pfad/zum/executable --functions --demangle adresse
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

