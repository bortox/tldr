---
author: ['b3nj4m1n', 'Nicolai Weitkemper', "Robby O'Connor", 'Guido Lena Cota', 'bl-ue', 'Daniel', 'marchersimon']
date: 1649277936
title: "tar"
description: "tar, Archivierungs Tool."
categories: "common"
---
> Häufig kombiniert mit anderen Methoden zur Komprimierung, wie gzip oder bzip2.

> Weitere Informationen: <https://www.gnu.org/software/tar>.

- Erstelle ein Archiv von Dateien:

```bash
tar cf pfad/zu/ziel.tar pfad/zu/datei1 pfad/zu/datei2 pfad/zu/datei3
```

- Erstelle ein mit gzip komprimiertes Archiv:

```bash
tar czf ziel.tar.gz pfad/zu/datei1 pfad/zu/datei2 pfad/zu/datei3
```

- Erstelle ein mit gzip komprimiertes Archiv mit relativen Pfaden:

```bash
tar czf pfad/zu/ziel.tar.gz -C pfad/zu/verzeichnis/ .
```

- Extrahiere ein (komprimiertes) Archiv in das derzeitige Verzeichnis:

```bash
tar xf pfad/zu/quelle.tar[.gz|.bz2|.xz]
```

- Extrahiere ein Archiv in ein Verzeichnis:

```bash
tar xf pfad/zu/quelle.tar -C verzeichnis
```

- Erstelle ein komprimiertes Archiv und benutze den Archiv Suffix um die Kompressionsmethode zu wählen:

```bash
tar caf ziel.tar.xz pfad/zu/datei1 pfad/zu/datei2 pfad/zu/datei3
```

- Führe die Inhalte eines tar Archivs auf:

```bash
tar tvf pfad/zu/quelle.tar
```

- Extrahiere Dateien die mit einem Muster übereinstimmen:

```bash
tar xf pfad/zu/quelle.tar --wildcards "*.html"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Nicolai Weitkemper](mailto:nico.weio@gmail.com) | tar: fix spelling in German translation (#7964) | 2022-04-06T22:45:36 | [9c3619928b58](https://github.com/tldr-pages/tldr/commit/9c3619928b5887124c035d1894a76786dfa742aa)
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | German pages: fix (valid) tldr-lint errors (#5363) | 2021-03-08T20:38:36 | [22ac7d5e0e34](https://github.com/tldr-pages/tldr/commit/22ac7d5e0e34bac2d1640ba3505be55eeabb2773)
[Robby O'Connor](mailto:rob@oconnor.ninja) | tar: fix bzip to bzip2 in command description (#5264) | 2021-02-13T04:53:30 | [5cd65c2850e0](https://github.com/tldr-pages/tldr/commit/5cd65c2850e0f3186af032337f596dbb7c5be79a)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[b3nj4m1n](mailto:b3nj4m1n@gmx.net) | tar: add German translation | 2020-07-02T17:41:08 | [db61bba6e7d6](https://github.com/tldr-pages/tldr/commit/db61bba6e7d663e2dd85727fa3a5977ec3fad6bf)

