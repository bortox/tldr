---
author: ['marchersimon']
date: 1619294218
title: "logcat, TLDR Pages"
description: "logcat, Gib ein Protokoll aller Systemmeldungen aus:"
categories: "android"
---
> Weitere Informationen: <https://developer.android.com/studio/command-line/logcat>.

- Gib ein Protokoll aller Systemmeldungen aus:

```bash
logcat
```

- Schreibe alle Systemmeldungen in eine Datei:

```bash
logcat -f pfad/zu/datei
```

- Gib Zeilen aus, die einem regulären Ausdruck entsprechen:

```bash
logcat --regex regex
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: add German translation (#5808) | 2021-04-24T21:56:58 | [906ccc19e4a5](https://github.com/tldr-pages/tldr/commit/906ccc19e4a52da93874a6797b29412359e658b4)

