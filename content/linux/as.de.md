---
author: ['MeerBiene', 'lincc', 'Daniel']
date: 1643487459
title: "as, TLDR Pages"
description: "as, Portabler GNU assembler."
categories: "linux"
---
> Hauptsächlich beabsichtigt um output von `gcc` für `ld` vorzubereiten.

> Weitere Informationen: <https://manned.org/as>.

- Assemble eine Datei und schreibe den Output in eine in `a.out`.

```bash
as datei.s
```

- Assemble den Output einer gegebenen Datei:

```bash
as datei.s -o out.o
```

- Generiere den Output schneller indem Leerzeichen und Kommentare nicht verarbeitet werden. (Sollte nur für vertrauenswürdige Compiler benutzt werden):

```bash
as -f datei.s
```

- Inkludiere einen gegebenen Pfad in der Liste von Verzeichnissen für die Suche nach Dateien:

```bash
as -I pfad/zum/verzeichnis datei.s
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

