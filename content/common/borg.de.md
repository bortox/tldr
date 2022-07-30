---
author: ['Frank Benedikt', 'bl-ue', 'marchersimon']
date: 1619262596
title: "borg"
description: "borg, Deduplizierendes Sicherungswerkzeug."
categories: "common"
---
> Erstellt lokale oder entfernte Sicherungen, die als Dateisysteme einhängbar sind.

> Weitere Informationen: <https://borgbackup.readthedocs.io/en/stable/usage/general.html>.

- Initialisiere ein lokales Repository:

```bash
borg init pfad/zu/repo_verzeichnis
```

- Sichere ein Verzeichnis in das Repository und erstelle ein Archiv mit dem Namen "Montag":

```bash
borg create --progress pfad/zu/repo_verzeichnis::Montag pfad/zu/quell_verzeichnis
```

- Liste alle Archive in einem Repository auf:

```bash
borg list pfad/zu/repo_verzeichnis
```

- Extrahiere ein bestimmtes Verzeichnis aus dem "Montag"-Archiv in einem entfernten Repository, unter Ausschluss aller `*.ext`-Dateien:

```bash
borg extract benutzer@host:pfad/zu/repo_verzeichnis::Montag pfad/zu/ziel_verzeichnis} --exclude '*.ext'
```

- Bereinige ein Repository, indem alle Archive gelöscht werden, die älter als 7 Tage sind und Änderungen aufweisen:

```bash
borg prune --keep-within 7d --list pfad/zu/repo_verzeichnis
```

- Hänge ein Repository als FUSE-Dateisystem ein:

```bash
borg mount pfad/zu/repo_verzeichnis::Montag pfad/zu/mountpoint
```

- Zeige Hilfe zur Erstellung von Archiven an:

```bash
borg create --help
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | German pages: fix (valid) tldr-lint errors (#5363) | 2021-03-08T20:38:36 | [22ac7d5e0e34](https://github.com/tldr-pages/tldr/commit/22ac7d5e0e34bac2d1640ba3505be55eeabb2773)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Frank Benedikt](mailto:63481435+FrankBG67@users.noreply.github.com) | German translation: alias, bash, borg, cd, chmod, chromium, chsh, convert, exa (#4132) Co-authored-by: Zlatan Vasović [...] | 2020-06-29T23:59:34 | [9aa5907281cb](https://github.com/tldr-pages/tldr/commit/9aa5907281cbaa7a0ee08b5c330c660d779282c7)

