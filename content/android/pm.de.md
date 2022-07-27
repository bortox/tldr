---
author: ['marchersimon']
date: 1619294218
title: "pm, TLDR Pages"
description: "pm, Zeige Informationen über Apps auf einem Android Gerät."
categories: "android"
---
> Weitere Informationen: <https://developer.android.com/studio/command-line/adb#pm>.

- Gib eine Liste aller installierten Apps aus:

```bash
pm list packages
```

- Gib eine Liste aller installierten System-Apps aus:

```bash
pm list packages -s
```

- Gib eine Liste aller installierten Apps von Drittanbietern aus:

```bash
pm list packages -3
```

- Gib eine Liste aller Apps, auf die ein bestimmtes Schlüsselwort zutrifft, aus:

```bash
pm list packages Schlüsselwort
```

- Gib den Pfad der APK einer bestimmten App aus:

```bash
pm path app
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: add German translation (#5808) | 2021-04-24T21:56:58 | [906ccc19e4a5](https://github.com/tldr-pages/tldr/commit/906ccc19e4a52da93874a6797b29412359e658b4)

