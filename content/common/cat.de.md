---
author: ['Daniel', 'Zlatan Vasović', 'Dario Vladović', 'Pascal Iske', 'marchersimon']
date: 1634914980
title: "cat, TLDR Pages"
description: "cat, Verkette und gib einzelne oder mehrere Dateien aus."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/cat>.

- Gib den Inhalt einer Datei aus:

```bash
cat pfad/zu/datei
```

- Verkette mehrere Dateien und speichere das Ergebnis in einer neuen Datei:

```bash
cat pfad/zu/datei1 pfad/zu/datei2 > pfad/zu/ziel_datei
```

- Verkette mehrere Dateien und hänge das Ergebnis an eine Datei an:

```bash
cat pfad/zu/datei1 pfad/zu/datei2 >> pfad/zu/ziel_datei
```

- Nummeriere alle ausgegebenen Zeilen:

```bash
cat -n pfad/zu/datei
```

- Gib eine Datei inklusive aller unsichtbaren Leerzeichen aus (mit `M-` Präfix wenn sie nicht ASCII sind):

```bash
cat -v -t -e pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | multiple pages: add missing periods (#3799) | 2020-01-25T15:49:48 | [6131069f1805](https://github.com/tldr-pages/tldr/commit/6131069f180563dba2b39d35e6f2c07d74d6e4e2)
[Pascal Iske](mailto:info@pascal-iske.de) | cat: add german translation (#3523) | 2019-11-02T18:51:30 | [9bc5fec2322d](https://github.com/tldr-pages/tldr/commit/9bc5fec2322dde5ca567b4f4734fe44d4740d862)

