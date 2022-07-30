---
author: ['marchersimon']
date: 1619294218
title: "am"
description: "am, Androids Aktivitäten-Manager."
categories: "android"
---
> Weitere Informationen: <https://developer.android.com/studio/command-line/adb#am>.

- Starte eine bestimmte Aktivität:

```bash
am start -n com.android.settings/.Settings
```

- Starte eine Aktivität und übergib ihr Daten:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Starte eine Aktivität, auf die eine bestimmte Aktion und Kategorie zutrifft:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Konvertiere ein bestimmtes Ziel in einen URI:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: add German translation (#5808) | 2021-04-24T21:56:58 | [906ccc19e4a5](https://github.com/tldr-pages/tldr/commit/906ccc19e4a52da93874a6797b29412359e658b4)

