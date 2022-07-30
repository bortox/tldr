---
author: ['Daniel', 'marchersimon']
date: 1634914980
title: "tlmgr"
description: "tlmgr, Verwalte Packages und Konfigurationen einer existierenden TeX Live Installation."
categories: "common"
---
> Manche Unterbefehle wie `tlmgr paper` sind separat dokumentiert.

> Weitere Informationen: <https://www.tug.org/texlive/tlmgr.html>.

- Installiere ein Package und seine Abhängigkeiten:

```bash
tlmgr install package
```

- Entferne ein Package und seine Abhängigkeiten:

```bash
tlmgr remove package
```

- Zeige Informationen über ein Package an:

```bash
tlmgr info package
```

- Aktualisiere alle Packages:

```bash
tlmgr update --all
```

- Zeige mögliche Aktualisierungen an, ohne Änderungen vorzunehmen:

```bash
tlmgr update --list
```

- Starte die grafische Oberfläche von tlmgr:

```bash
tlmgr gui
```

- Liste alle Tex Live Konfigurationen auf:

```bash
tlmgr conf
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-paper: add page (#6463) | 2021-09-05T07:18:06 | [06861b8aa908](https://github.com/tldr-pages/tldr/commit/06861b8aa90800d34820d585c68bae23d8fe471a)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | latex, pdflatex, pdftex, tex, texdoc, texliveonfly, tlmgr: add German translation (#5305) | 2021-02-28T15:27:55 | [d9e1df0c2ed2](https://github.com/tldr-pages/tldr/commit/d9e1df0c2ed2c9b684791ed538e276c9ed3cdfd8)

