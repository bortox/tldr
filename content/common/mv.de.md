---
author: ['Daniel', 'Dario Vladović', 'Pascal Iske', 'Alessio', 'marchersimon']
date: 1634914980
title: "mv, TLDR Pages"
description: "mv, Verschiebe Dateien oder Verzeichnisse oder benenne diese um."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/mv>.

- Verschiebe eine Datei an einen beliebigen Ort:

```bash
mv pfad/zu/datei pfad/zu/zieldatei
```

- Verschiebe mehrere Dateien in ein anderes Verzeichnis und behalte deren Namen bei:

```bash
mv datei1 datei2 datei3 pfad/zu/ziel_verzeichnis
```

- Überschreibe bereits existierende Dateien ohne vorherige Bestätigung:

```bash
mv -f pfad/zu/datei pfad/zu/zieldatei
```

- Überschreibe bereits existierende Dateien nach Bestätigung (unabhängig von Dateirechten):

```bash
mv -i pfad/zu/datei pfad/zu/zieldatei
```

- Verhindere das Überschreiben existierender Dateien am Zielort:

```bash
mv -n pfad/zu/datei pfad/zu/zieldatei
```

- Liste Dateien und deren Details auf während sie verschoben werden:

```bash
mv -v pfad/zu/datei pfad/zu/zieldatei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Alessio](mailto:25589202+tomadojuice@users.noreply.github.com) | mv: add more information link (#5542) | 2021-03-29T20:24:45 | [45ff3b27a290](https://github.com/tldr-pages/tldr/commit/45ff3b27a290a760ee43340226e4e85e2091dbfc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Pascal Iske](mailto:info@pascal-iske.de) | mv: add german translation | 2019-11-02T18:52:30 | [be012a2dd7e7](https://github.com/tldr-pages/tldr/commit/be012a2dd7e728ac629af09e04bfc588cc7d1efd)

