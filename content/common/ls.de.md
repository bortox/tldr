---
author: ['Dario Vladović', 'Axel Navarro', 'marchersimon', 'Pascal Iske']
date: 1626631245
title: "ls, TLDR Pages"
description: "ls, Liste den Inhalt eines Verzeichnisses auf."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/ls>.

- Liste den Inhalt in einer Datei pro Zeile auf:

```bash
ls -1
```

- Liste alle Dateien inklusive versteckter Dateien auf:

```bash
ls -a
```

- Liste alle Dateien mit einem abschließenden `/` bei Verzeichnis-Namen auf:

```bash
ls -F
```

- Liste alle Dateien mit Berechtigungen, Besitzer, Größe und Änderungsdatum auf:

```bash
ls -la
```

- Liste alle Dateien mit Dateigröße in für Menschen lesbaren Einheiten (KiB, MiB, GiB):

```bash
ls -lh
```

- Liste Dateien nach sortiert nach Dateigröße mit größter beginnend auf:

```bash
ls -lS
```

- Liste alle Dateien sortiert nach dem Änderungsdatum mit ältester beginnend auf:

```bash
ls -ltr
```

- Liste nur Verzeichnisse auf:

```bash
ls -d */
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[Pascal Iske](mailto:info@pascal-iske.de) | ls: add german translation | 2019-11-02T18:52:30 | [08e87648945a](https://github.com/tldr-pages/tldr/commit/08e87648945ad786d452064f6ce272e304f6b637)

