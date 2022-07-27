---
author: ['Sebastian Göls', 'CleanMachine1', 'marchersimon']
date: 1625254726
title: "gcc, TLDR Pages"
description: "gcc, Präprozessiert und kompiliert C und C++ Quellcodedateien und linkt diese anschließend zusammen."
categories: "common"
---
> Weitere Informationen: <https://gcc.gnu.org>.

- Kompiliere mehrere Quellcodedateien zu einer ausführbaren Datei:

```bash
gcc pfad/zu/datei1.c pfad/zu/datei2.c --output pfad/zu/binärdatei
```

- Erlaube Warnungen und debug-Symbole in der Ausgabedatei:

```bash
gcc pfad/zu/datei.c -Wall -Og --output pfad/zu/binärdatei
```

- Inkludiere Bibliotheken aus anderen Verzeichnissen:

```bash
gcc pfad/zu/datei.c --output pfad/zu/binärdatei -Ipfad/zu/headerdatei -Lpfad/zu/bibliothek1 -lpfad/zu/bibliothek2
```

- Kompiliere Quellcodedateien zu Assemblerinstruktionen:

```bash
gcc -S pfad/zu/datei.c
```

- Kompiliere eine oder mehrere Quellcodedateien ohne diese zu linken:

```bash
gcc -c pfad/zu/datei.c
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | gcc: add long flag (#6182) | 2021-07-02T21:38:46 | [4c0aa1ac0cb7](https://github.com/tldr-pages/tldr/commit/4c0aa1ac0cb7541cd982040668faad0d842aa1a2)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Sebastian Göls](mailto:6608231+Abrynos@users.noreply.github.com) | gcc: add German translation (#4760) | 2020-10-19T20:11:46 | [450573532cf4](https://github.com/tldr-pages/tldr/commit/450573532cf417f820b9767592c2d32d9966b485)

