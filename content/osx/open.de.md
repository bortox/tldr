---
author: ['Kargins', 'marchersimon', 'git-em']
date: 1646140877
title: "open, TLDR Pages"
description: "open, Öffne Dateien, Verzeichnisse und Anwendungen."
categories: "osx"
---
> Weitere Informationen: <https://ss64.com/osx/open.html>.

- Öffne eine Datei in der zugehörigen Anwendung:

```bash
open pfad/zu/datei
```

- Führe eine grafische macOS-Anwendung aus:

```bash
open -a anwendung
```

- Führe eine grafische macOS-Anwendung basierend auf der Bundle-Kennung aus (siehe `osascript` für eine einfache Möglichkeit, diese zu identifizieren):

```bash
open -b com.domain.anwendung
```

- Öffne das aktuelle Verzeichnis im Finder:

```bash
open .
```

- Zeige eine Datei im Finder an:

```bash
open -R pfad/zu/datei
```

- Öffne alle Dateien einer bestimmten Erweiterung im aktuellen Verzeichnis mit der zugehörigen Anwendung:

```bash
open *.ext
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | brightness, n, open, pbcopy, pbpaste, rename, route, rubocop, softwareupdate, timed, where, while, xed, xip: add link (#7831) | 2022-03-01T14:21:17 | [2ce63b334ebd](https://github.com/tldr-pages/tldr/commit/2ce63b334ebd26bb9e46be904fcc19884974e397)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Kargins](mailto:GETandSELECT@users.noreply.github.com) | brew-bundle, caffeinate, open and tmutil: add German translation (#5178) * brew-bundle, caffeinate, open and tmutil: add German [...] | 2021-01-24T17:23:41 | [50cff8c9e6cc](https://github.com/tldr-pages/tldr/commit/50cff8c9e6ccb71814f52be4a517f8a07b51cd0f)

