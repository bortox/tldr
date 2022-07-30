---
author: ['marchersimon']
date: 1619262596
title: "texliveonfly"
description: "texliveonfly, Lade fehlende TeX Live Packages während dem Kompilieren einer `.tex` Datei herunter."
categories: "common"
---
> Weitere Informationen: <https://ctan.org/pkg/texliveonfly>.

- Lade fehlende Packages während dem Kompilieren herunter:

```bash
texliveonfly quelldatei.tex
```

- Verwende einen bestimmten Compiler (standardmäßig `pdflatex`):

```bash
texliveonfly --compiler=compiler quelldatei.tex
```

- Verwende ein bestimmtes Tex Live `bin` Verzeichnis:

```bash
texliveonfly --texlive_bin=pfad/zu/texlive_bin quelldatei.tex
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | latex, pdflatex, pdftex, tex, texdoc, texliveonfly, tlmgr: add German translation (#5305) | 2021-02-28T15:27:55 | [d9e1df0c2ed2](https://github.com/tldr-pages/tldr/commit/d9e1df0c2ed2c9b684791ed538e276c9ed3cdfd8)

