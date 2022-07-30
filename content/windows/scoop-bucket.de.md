---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "scoop bucket"
description: "scoop bucket, Verwalte 'Eimer': Git-Repositories, welche Dateien enthalten, die beschreiben, wie Scoop Programme installiert werden."
categories: "windows"
---
> Kennt Scoop nicht die URL eines Eimers, so muss diese angegeben werden.

> Weitere Informationen: <https://github.com/lukesampson/scoop/wiki/Buckets>.

- Liste alle Eimer auf, die gerade aktiv sind:

```bash
scoop bucket list
```

- Liste alle bekannten Eimer auf:

```bash
scoop bucket known
```

- Aktiviere einen bekannten Eimer:

```bash
scoop bucket add name
```

- Aktiviere einen unbekannten Eimer durch die Angabe eines Namens und einer Git-Repository-URL:

```bash
scoop bucket add name https://beispiel.de/repository.git
```

- Deaktiviere einen Eimer:

```bash
scoop bucket rm name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[LukBukkit](mailto:luk.bukkit@gmail.com) | scoop-bucket: add German translation | 2020-10-15T00:35:19 | [3c23ab75bfc3](https://github.com/tldr-pages/tldr/commit/3c23ab75bfc395bdb2ea0a2ddcb6203dfd77bc84)

