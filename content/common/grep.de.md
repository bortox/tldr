---
author: ['marchersimon']
date: 1619262596
title: "grep"
description: "grep, Findet Ausdrücke in einem Eingabetext."
categories: "common"
---
> Unterstützt einfache Muster und reguläre Ausdrücke.

> Weitere Informationen: <https://www.gnu.org/software/grep/manual/grep.html>.

- Suche nach einem Ausdruck in einer Datei:

```bash
grep ausdruck pfad/zu/datei
```

- Suche nach einem exakten Ausdruck:

```bash
grep -F exakter_ausdruck pfad/zu/datei
```

- Suche nach Ausdrücken [R]ekursiv im aktuellen Verzeichnis, zeige zugehörige Zeilen[n]ummern und [I]gnoriere Binärdateien:

```bash
grep -RIn ausdruck .
```

- Benutze erweiterte reguläre Ausdrücke (unterstützt `?`, `+`, `{}`, `()` und `|`) ohne Beachtung der Groß-, Kleinschreibung:

```bash
grep -Ei ausdruck pfad/zu/datei
```

- Zeige 3 Zeilen Kontext um [C], vor [B] oder nach [A] jedem Ergebnis:

```bash
grep -C|B|A 3 ausdruck pfad/zu/datei
```

- Gib den Dateinamen mit zugehöriger Zeilennummer für jedes Ergebnis aus:

```bash
grep -Hn ausdruck pfad/zu/datei
```

- Benutze STDIN, anstatt einer Datei:

```bash
echo "input" | grep ausdruck
```

- In[v]ertiere das Ergebnis um bestimmte Ausdrücke auszuschließen:

```bash
grep -v ausdruck
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | grep: edit link (#5782) | 2021-04-18T00:08:17 | [d934ae39644f](https://github.com/tldr-pages/tldr/commit/d934ae39644f2ce38f61505d40642a742e9f4c10)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo, fdroid, fdroidcl, ffprobe, ffsend, fg, firefox, fortune, fuck, g++, gdb, gpg2, grep: add German translation (#5361) | 2021-03-07T15:12:23 | [621355ceaf12](https://github.com/tldr-pages/tldr/commit/621355ceaf120c12636ae359cdf108678acd89db)

