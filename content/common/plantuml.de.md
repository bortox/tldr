---
author: ['Florian', 'bl-ue', 'Daniel', 'marchersimon']
date: 1634914980
title: "plantuml"
description: "plantuml, Erstelle UML-Diagramme aus einer reinen Textsprache und rendere sie in verschiedenen Formaten."
categories: "common"
---
> Weitere Informationen: <https://plantuml.com/en/command-line>.

- Rendere Diagramme im Standardformat (PNG):

```bash
plantuml pfad/zu/diagramm1.puml pfad/zu/diagramm2.puml
```

- Rendere eine Diagramm im vorgegebenen Format (z.B. `png`, `pdf`, `svg`, `txt`):

```bash
plantuml -t format pfad/zu/diagramm.puml
```

- Rendere alle Diagramme eines Verzeichnisses:

```bash
plantuml pfad/zu/verzeichnis
```

- Rendere ein Diagramm in ein bestimmtes Ausgabeverzeichnis:

```bash
plantuml -o pfad/zu/verzeichnis pfad/zu/diagramm.puml
```

- Rendere ein Diagramm mit einer bestimmten Konfigurationsdatei:

```bash
plantuml -config pfad/zu/konfig.cfg pfad/zu/diagramm.puml
```

- Zeige Hilfe an:

```bash
plantuml -help
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Florian](mailto:40308458+ProfileID@users.noreply.github.com) | 7z, ansible-playbook, ansible-vault, plantuml: add german translation (#4234) | 2020-08-02T20:47:28 | [bb6f6dbe3793](https://github.com/tldr-pages/tldr/commit/bb6f6dbe37937d552739f11596e75918a49d9356)

