---
author: ['b3nj4m1n', 'marchersimon']
date: 1658125216
title: "zsh"
description: "zsh, Z SHell."
categories: "common"
---
> Mit `bash` und `sh` kompatible Eingabeaufforderung.

> Weitere Informationen: <https://www.zsh.org>.

- Starte eine interaktive Eingabeaufforderung:

```bash
zsh
```

- Führe Parameter als Befehl aus:

```bash
zsh -c befehl
```

- Führe Befehle aus einem Skript aus:

```bash
zsh pfad/zu/skript
```

- Führe Befehle aus einem Skript aus und schreibe die Befehle in die Konsole:

```bash
zsh --xtrace pfad/zu/skript
```

- Starte eine interaktive Eingabeaufforderung, in der jeder Befehl ausgegeben wird, bevor er ausgeführt wird:

```bash
zsh --verbose
```

- Führe einen Befehl innerhalb von `zsh` mit ausgeschalteten Glob-Mustern aus:

```bash
noglob befehl
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | zsh: add noglob example (#8179) * zsh: add noglob example Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2022-07-18T08:20:16 | [30ec44ef4352](https://github.com/tldr-pages/tldr/commit/30ec44ef43522640943b204954dcd298f1e434e4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[b3nj4m1n](mailto:b3nj4m1n@gmx.net) | zsh: add German translation | 2020-07-02T17:41:08 | [00e7938c99c0](https://github.com/tldr-pages/tldr/commit/00e7938c99c0103606d08e25560b7dcaf459c4a9)

