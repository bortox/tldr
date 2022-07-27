---
author: ['Craxy', 'Muhammad Falak R Wani', 'marchersimon']
date: 1635631367
title: "git log, TLDR Pages"
description: "git log, Zeigt die Commit-Historie an."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-log>.

- Zeige die Sequenz der Commits des Git-Repository im aktuellen Verzeichnis, beginnend mit dem aktuellen, an.

```bash
git log
```

- Zeige die Historie einer bestimmten Datei oder eines Verzeichnisses, inklusive Unterschiede, an:

```bash
git log -p pfad/zu/datei_oder_verzeichnis
```

- Zeige einen Überblick der Commits an und welche Dateien jeweils verändert wurden:

```bash
git log --stat
```

- Zeige einen Graphen von Commits im aktuellen Branch, wobei jeweils nur die erste Zeile der Commit-Nachricht angezeigt wird:

```bash
git log --oneline --graph
```

- Zeige einen Graphen von allen Commits, Tags und Branches im gesamten Repository:

```bash
git log --oneline --decorate --all --graph
```

- Zeige nur Commits, deren Commit-Nachricht einen bestimmten Text enthalten (Ohne Beachtung von Groß- und Kleinschreibung):

```bash
git log -i --grep text
```

- Zeige die letzten N Commits eines bestimmten Autors:

```bash
git log -n anzahl --author=autor
```

- Zeige alle Commits zwischen zwei Zeitpunkten an (yyyy-mm-dd):

```bash
git log --before="2017-01-29" --after="2017-01-17"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | git-log: clarify date format with example (#7150) | 2021-10-31T00:02:47 | [11f811cc994d](https://github.com/tldr-pages/tldr/commit/11f811cc994ddea4ff4dd07d254b0da120d2dc18)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Craxy](mailto:16610792+CraxyTM@users.noreply.github.com) | git-log: add German translation (#4726) | 2020-11-02T16:53:52 | [54a9f50dba7d](https://github.com/tldr-pages/tldr/commit/54a9f50dba7d1e5ce0717d03910752bd07d03f26)

