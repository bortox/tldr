---
author: ['marchersimon']
date: 1619294218
title: "settings"
description: "settings, Verwalte Android-Systemeinstellungen."
categories: "android"
---
> Weitere Informationen: <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- Gib eine Liste aller Einstellungen im Namespace `global` aus:

```bash
settings list global
```

- Gib den Wert einer bestimmten Einstellung aus:

```bash
settings get global airplane_mode_on
```

- Setze den Wert einer bestimmten Einstellung:

```bash
settings put system screen_brightness 42
```

- Lösche eine bestimmte Einstellung:

```bash
settings delete secure screensaver_enabled
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: add German translation (#5808) | 2021-04-24T21:56:58 | [906ccc19e4a5](https://github.com/tldr-pages/tldr/commit/906ccc19e4a52da93874a6797b29412359e658b4)

