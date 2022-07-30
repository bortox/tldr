---
author: ['marchersimon']
date: 1619262596
title: "pdftex"
description: "pdftex, Kompiliere eine TeX Quelldatei in ein PDF Dokument."
categories: "common"
---
> Weitere Informationen: <https://www.tug.org/applications/pdftex/>.

- Kompiliere ein PDF Dokument:

```bash
pdftex quelldatei.tex
```

- Kompiliere ein PDF Dokument und gib ein bestimmtes Output-Verzeichnis an:

```bash
pdftex -output-directory=pfad/zu/verzeichnis quelldatei.tex
```

- Kompiliere ein PDF Dokument und stoppe bei jedem Fehler:

```bash
pdftex -halt-on-error quelldatei.tex
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | latex, pdflatex, pdftex, tex, texdoc, texliveonfly, tlmgr: add German translation (#5305) | 2021-02-28T15:27:55 | [d9e1df0c2ed2](https://github.com/tldr-pages/tldr/commit/d9e1df0c2ed2c9b684791ed538e276c9ed3cdfd8)

