---
author: ['marchersimon']
date: 1619262596
title: "gdb, TLDR Pages"
description: "gdb, Der GNU Debugger."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/gdb>.

- Debugge eine ausführbare Datei:

```bash
gdb ausführbare_datei
```

- Binde einen Prozess an gdb:

```bash
gdb -p prozess_ID
```

- Debugge mit einer Kerndatei:

```bash
gdb -c kerndatei ausführbare_datei
```

- Führe angegebene Befehle beim Start von gdb aus:

```bash
gdb -ex "befehle" ausführbare_datei
```

- Starte gdb und übergib Argumente an die ausführbare Datei:

```bash
gdb --args ausführbare_datei argument1 argument2
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

