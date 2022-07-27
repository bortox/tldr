---
author: ['Kasjan Chilarski', 'marchersimon']
date: 1634848494
title: "du, TLDR Pages"
description: "du, Disk usage: Plattenplatzverbrauch von Dateien und Verzeichnissen ermitteln."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/du>.

- Liste die Größe von Verzeichnissen und Unterverzeichnissen in den gegebenen Einheiten (B/KiB/MiB) auf:

```bash
du -b|k|m pfad/zu/verzeichnis
```

- Liste die Größe von Verzeichnissen und Unterverzeichnissen in menschenlesbaren Einheiten auf (d.h. automatische Auswahl der geeigneten Einheit für jede Größe):

```bash
du -h pfad/zu/verzeichnis
```

- Zeige die Größe eines einzelnen Verzeichnisses in menschenlesbaren Einheiten:

```bash
du -sh pfad/zu/verzeichnis
```

- Liste die Größe von Verzeichnissen und Unterverzeichnissen und aller ihrer Dateien in menschenlesbaren Einheiten auf:

```bash
du -ah pfad/zu/verzeichnis
```

- Liste die menschenlesbaren Größen eines Verzeichnisses und aller Unterverzeichnisse, bis zu einer Tiefe von `N` Ebenen:

```bash
du -h --max-depth=N pfad/zu/verzeichnis
```

- Liste die menschenlesbare Größe aller `.jpg`-Dateien in Unterverzeichnissen des aktuellen Verzeichnisses auf und zeige am Ende die kumulierte Gesamtsumme an:

```bash
du -ch */*.jpg
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: fix wrong byte units (#7131) | 2021-10-21T22:34:54 | [0ddea62ffb82](https://github.com/tldr-pages/tldr/commit/0ddea62ffb822afabf0437c9a0d15258f13ce672)
[Kasjan Chilarski](mailto:keistzen@gmail.com) | du: add German translation (#6693) | 2021-10-03T16:56:14 | [b62bbde4160b](https://github.com/tldr-pages/tldr/commit/b62bbde4160b4d8ccfdbbf8a0099758daf7c90de)

