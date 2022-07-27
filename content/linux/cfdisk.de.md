---
author: ['Mat', 'bl-ue', 'marchersimon']
date: 1619262596
title: "cfdisk, TLDR Pages"
description: "cfdisk, Ein Programm zur Verwaltung von Partitionstabellen mittels einer Curses-basierten UI."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/cfdisk>.

- Öffne das Partitionierungsinterface für eine bestimmte Festplatte:

```bash
cfdisk /dev/sdX
```

- Erzeuge und bearbeite eine neue Partitionierungstabelle für eine bestimmte Festplatte:

```bash
cfdisk --zero /dev/sdX
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | German pages: fix (valid) tldr-lint errors (#5363) | 2021-03-08T20:38:36 | [22ac7d5e0e34](https://github.com/tldr-pages/tldr/commit/22ac7d5e0e34bac2d1640ba3505be55eeabb2773)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Mat](mailto:mtausig@users.noreply.github.com) | cfdisk: add page (#4881) | 2020-10-28T19:39:33 | [15fa534d4b55](https://github.com/tldr-pages/tldr/commit/15fa534d4b55fb6a509d49f1f195cf13f2b2c253)

