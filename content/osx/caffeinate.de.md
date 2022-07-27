---
author: ['Kargins', 'Kyle', 'marchersimon', 'Daniel']
date: 1634914980
title: "caffeinate, TLDR Pages"
description: "caffeinate, Hindert den Mac daran, in den Schlaf-Modus zu gehen."
categories: "osx"
---
> Weitere Informationen: <https://ss64.com/osx/caffeinate.html>.

- Halte den Mac für 1 Stunde (3600 Sekunden) wach:

```bash
caffeinate -u -t 3600
```

- Halte den Mac wach, bis ein bestimmter Befehl abgeschlossen ist:

```bash
caffeinate -s befehl
```

- Halte den Mac wach, bis `caffeinate` durch Cmd-C beendet wird:

```bash
caffeinate -i
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Kargins](mailto:GETandSELECT@users.noreply.github.com) | brew-bundle, caffeinate, open and tmutil: add German translation (#5178) * brew-bundle, caffeinate, open and tmutil: add German [...] | 2021-01-24T17:23:41 | [50cff8c9e6cc](https://github.com/tldr-pages/tldr/commit/50cff8c9e6ccb71814f52be4a517f8a07b51cd0f)

