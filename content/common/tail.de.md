---
author: ['Spicyyboi']
date: 1636232836
title: "tail, TLDR Pages"
description: "tail, Gib das Ende einer Datei aus."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/tail>.

- Zeige die letzten Zeilen einer Datei an:

```bash
tail -n anzahl_an_zeilen datei
```

- Zeige alle Zeilen einer Datei ab einer bestimmten Zeile an:

```bash
tail -n +zeile datei
```

- Zeige die letzten Bytes einer Datei an:

```bash
tail -c anzahl_an_bytes datei
```

- Lies aus einer Datei, bis `Ctrl + C` gedrückt wird:

```bash
tail -f datei
```

- Lies aus einer Datei, bis `Ctrl + C` gedrückt wird, selbst, wenn die Datei nicht zugänglich ist:

```bash
tail -F datei
```

- Zeige die letzten Zeilen einer Datei an und lade alle paar Sekunden neu:

```bash
tail -n anzahl_an_zeilen -s anzahl_an_sekunden -f datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Spicyyboi](mailto:34308782+spicyyboi@users.noreply.github.com) | head, tail: add German translation (#7301) | 2021-11-06T22:07:16 | [3c3d11345a18](https://github.com/tldr-pages/tldr/commit/3c3d11345a18ddcc24419c2dd10e3d27da197fe3)

