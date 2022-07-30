---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "arithmetic"
description: "arithmetic, Quiz über simple arithmetische Probleme."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/bsdgames/arithmetic.6.en.html>.

- Starte ein arithmetisches Quiz:

```bash
arithmetic
```

- Spezifiziere einen oder mehr arithemtische [O]peratoren um Probleme mit ihnen zu bekommen:

```bash
arithmetic -o +|-|x|/
```

- Gib eine Reichweite. Additions- und Multiplikationsprobleme werden Zahlen zwischen 0 und der gegebenen Reichweite enthalten. Subtraktionen und Divisionen werden Zahlen zwischen -1 und der gegebenen Reichweite enthalten.

```bash
arithmetic -r 7
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

