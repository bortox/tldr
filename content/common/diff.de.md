---
author: ['marchersimon']
date: 1619262596
title: "diff"
description: "diff, Vergleiche Dateien und Verzeichnisse."
categories: "common"
---
> Weitere Informationen: <https://man7.org/linux/man-pages/man1/diff.1.html>.

- Vergleiche Dateien (Listet jene Veränderungen auf, mit denen `datei1` zu `datei2` wird):

```bash
diff pfad/zu/datei1 pfad/zu/datei2
```

- Vergleiche Dateien und ignoriere Leerzeichen:

```bash
diff -w pfad/zu/datei1 pfad/zu/datei2
```

- Vergleiche Dateien und zeige Unterschiede nebeneinander:

```bash
diff -y pfad/zu/datei1 pfad/zu/datei2
```

- Vergleiche Dateien und zeige Unterschiede in vereinheitlichtem Format (wie in `git diff`):

```bash
diff -u pfad/zu/datei1 pfad/zu/datei2
```

- Vergleiche Verzeichnisse rekursiv (zeigt sowohl Namen von unterschiedlichen Dateien/Verzeichnissen, als auch Unterschiede zwischen Dateien):

```bash
diff -r altes_verzeichnis neues_verzeichnis
```

- Vergleiche Verzeichnisse und zeige nur die Namen der Dateien, die unterschiedlich sind:

```bash
diff -rq altes_verzeichnis neues_verzeichnis
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

