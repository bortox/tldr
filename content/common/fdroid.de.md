---
author: ['marchersimon']
date: 1619262596
title: "fdroid, TLDR Pages"
description: "fdroid, F-Droid Build Tool."
categories: "common"
---
> F-Droid ist ein installierbarer Katalog mit FOSS (Freie Open Source Software) Apps für Android.

> Weitere Informationen: <https://f-droid.org/>.

- Kompiliere eine bestimmte App:

```bash
fdroid build app_id
```

- Kompiliere eine bestimmte App in einer Build-Server-VM:

```bash
fdroid build app_id --server
```

- Veröffentliche die App im lokalen Repository:

```bash
fdroid publish app_id
```

- Installiere die App auf jedem verbundenen Gerät:

```bash
fdroid install app_id
```

- Überprüfe, ob die Metadaten korrekt formatiert sind:

```bash
fdroid lint --format app_id
```

- Korrigiere die Formatierung automatisch (wenn möglich):

```bash
fdroid rewritemeta app_id
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

