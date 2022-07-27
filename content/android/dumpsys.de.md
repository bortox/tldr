---
author: ['marchersimon']
date: 1619294218
title: "dumpsys, TLDR Pages"
description: "dumpsys, Stelle Informationen über Android-Systemservices bereit."
categories: "android"
---
> Dieser Befehl kann nur mit `adb shell` verwendet werden.

> Weitere Informationen: <https://developer.android.com/studio/command-line/dumpsys>.

- Erhalte diagnostische Informationen über alle Systemservices:

```bash
dumpsys
```

- Erhalte diagnostische Informationen über einen bestimmten Systemservice:

```bash
dumpsys service
```

- Liste alle Services, über die `dumpsys` Informationen bereitstellen kann auf:

```bash
dumpsys -l
```

- Liste Service-spezifische Argumente für einen Service auf:

```bash
dumpsys service -h
```

- Schließe einen bestimmten Service von den diagnostischen Informationen aus:

```bash
dumpsys --skip service
```

- Gib ein Timeout in Sekunden an (standardmäßig 10s):

```bash
dumpsys -t sekunden
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: add German translation (#5808) | 2021-04-24T21:56:58 | [906ccc19e4a5](https://github.com/tldr-pages/tldr/commit/906ccc19e4a52da93874a6797b29412359e658b4)

