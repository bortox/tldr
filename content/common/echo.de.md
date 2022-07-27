---
author: ['Dario Vladović', 'marchersimon']
date: 1619262596
title: "echo, TLDR Pages"
description: "echo, Gib angegebene Argumente aus."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/echo>.

- Gib einen Text aus. (Hinweis: Anführungszeichen sind optional):

```bash
echo "Hallo Welt"
```

- Gib einen Text mit Umgebungsvariablen aus:

```bash
echo "Liste aller Systempfade: $PATH"
```

- Gib einen Text ohne darauffolgenden Zeilenumbruch aus:

```bash
echo -n "Hallo Welt"
```

- Füge einen Text in eine Datei ein:

```bash
echo "Hallo Welt" >> datei.txt
```

- Ermögliche Interpretation von Fluchtsymbolen (backslash escape):

```bash
echo -e "Spalte 1\tSpalte 2"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo: add link (#5606) | 2021-03-30T15:54:21 | [206703144d57](https://github.com/tldr-pages/tldr/commit/206703144d576491dbcf66be20770c47ebe329d3)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

