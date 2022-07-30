---
author: ['Daniel Wolbach', 'Daniel', 'marchersimon']
date: 1634914980
title: "bat"
description: "bat, Ausgabe und Verkettung von einzelnen Dateien."
categories: "common"
---
> Ein `cat`-Ersatz mit Syntax-Hervorhebung und Git-Integration.

> Weitere Informationen: <https://github.com/sharkdp/bat>.

- Gib den Inhalt einer Datei in stdout aus:

```bash
bat pfad/zu/datei
```

- Verkette mehrere Dateien zu eine Zieldatei:

```bash
bat pfad/zu/datei1 pfad/zu/datei2 > pfad/zu/ziel_datei
```

- Hänge mehrere Dateien an eine Zieldatei an:

```bash
bat pfad/zu/datei1 pfad/zu/datei2 >> pfad/zu/ziel_datei
```

- Nummeriere alle ausgegebenen Zeilen:

```bash
bat -n pfad/zu/datei
```

- Hebe den Syntax einer JSON-Datei hervor:

```bash
bat --language json pfad/zu/datei.json
```

- Zeige alle unterstützten Sprachen an:

```bash
bat --list-languages
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Daniel Wolbach](mailto:daniel.wolbach@mailo.com) | bat: add German translation (#4537) | 2020-10-07T16:32:40 | [57c7f783bdc6](https://github.com/tldr-pages/tldr/commit/57c7f783bdc666084893955767666d1d758b4b83)

