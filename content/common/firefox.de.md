---
author: ['marchersimon', 'Daniel']
date: 1634914980
title: "firefox, TLDR Pages"
description: "firefox, Ein gratis Open Source Internet Browser."
categories: "common"
---
> Weitere Informationen: <https://developer.mozilla.org/en-US/docs/Mozilla/Command_Line_Options>.

- Starte Firefox und öffne eine Website:

```bash
firefox https://www.duckduckgo.com
```

- Öffne ein neues Fenster:

```bash
firefox --new-window https://www.duckduckgo.com
```

- Öffne ein privates (Inkognito) Fenster:

```bash
firefox --private-window
```

- Suche nach "wikipedia" mit der Standard-Suchmaschine:

```bash
firefox --search "wikipedia"
```

- Starte Firefox im sicheren Modus (alle Erweiterungen sind deaktiviert):

```bash
firefox --safe-mode
```

- Erstelle eine Bildschirmaufnahme einer Website, ohne die GUI zu starten:

```bash
firefox --headless --screenshot pfad/zu/ausgabedatei.png https://beispiel.de/
```

- Verwende ein bestimmtes Profil um mehrere einzelne Instanzen gleichzeitig laufen zu lassen:

```bash
firefox --profile pfad/zu/verzeichnis https://beispiel.de/
```

- Lege Firefox als Standard-Browser fest:

```bash
firefox --setDefaultBrowser
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

