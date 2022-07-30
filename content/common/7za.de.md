---
author: ['trolzen', 'marchersimon']
date: 1634591417
title: "7za"
description: "7za, Ein Dateiarchivierer mit hoher Kompressionsrate."
categories: "common"
---
> Eine alleinstehende Version von `7z` mit Unterstützung für neuere Archivtypen.

> Weitere Informationen: <https://www.7-zip.org>.

- [a]rchiviere eine Datei oder ein Verzeichnis:

```bash
7za a pfad/zu/archiv.7z pfad/zu/datei_oder_verzeichnis
```

- Verschlüssle ein vorhandenes Archiv (einschließlich Dateinamen):

```bash
7za a pfad/zu/verschlüsselt.7z -ppasswort -mhe=on pfad/zu/archiv.7z
```

- E[x]trahiere ein Archiv und behalte die originale Verzeichnisstruktur bei:

```bash
7za x pfad/zu/archiv.7z
```

- E[x]trahiere ein Archiv in ein bestimmtes Verzeichnis:

```bash
7za x pfad/zu/archiv.7z -opfad/zu/verzeichnis
```

- E[x]trahiere ein Archiv nach stdout:

```bash
7za x pfad/zu/archiv.7z -so
```

- [a]rchiviere mit einem bestimmten Archivtyp:

```bash
7za a -t7z|bzip2|gzip|lzip|tar|zip pfad/zu/archiv.7z pfad/zu/datei_oder_verzeichnis
```

- [l]iste den Inhalt einer Archivdatei auf:

```bash
7za l pfad/zu/archiv.7z
```

- Liste alle verfügbaren Archivtypen auf:

```bash
7za i
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[trolzen](mailto:trolzen@gmail.com) | 7z, 7za, 7zr: update list of archive formats (#7079) | 2021-10-18T23:10:17 | [1c07b17a6c31](https://github.com/tldr-pages/tldr/commit/1c07b17a6c319eb4d72fd840ee479565893bc3f1)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

