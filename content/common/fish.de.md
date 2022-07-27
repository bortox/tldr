---
author: ['b3nj4m1n', 'marchersimon']
date: 1619893215
title: "fish, TLDR Pages"
description: "fish, The Friendly Interactive SHell."
categories: "common"
---
> Eine benutzerfreundliche Eingabeaufforderung.

> Weitere Informationen: <https://fishshell.com>.

- Starte eine interaktive Shell-Sitzung:

```bash
fish
```

- Führe einen Befehl aus:

```bash
fish -c "befehl"
```

- Führe ein Skript aus:

```bash
fish pfad/zu/skript.fish
```

- Überprüfe ein Skript auf Syntaxfehler:

```bash
fish --no-execute pfad/zu/skript.fish
```

- Starte eine private interaktive Shell-Sitzung, in der `fish` weder auf die Shell-History zugreift, noch diese verändert:

```bash
fish --private
```

- Gib die Version von fish aus:

```bash
fish --version
```

- Setze und exportiere eine permanente Umgebungsvariable (nur innerhalb der Shell):

```bash
set -Ux variablenname variablenwert
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[b3nj4m1n](mailto:b3nj4m1n@gmx.net) | fish: add German translation | 2020-07-02T17:41:08 | [1efcde225ffc](https://github.com/tldr-pages/tldr/commit/1efcde225ffc09d93b716ee8f7f04ff83bf54f15)

