---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco pin, TLDR Pages"
description: "choco pin, Hefte ein Chocolatey-Paket bei einer bestimmten Version an."
categories: "windows"
---
> Angeheftete Pakete werden nicht weiter aktualisiert.

> Weitere Informationen: <https://chocolatey.org/docs/commands-pin>.

- Zeige eine Liste der angehefteten Pakete und ihrer Versionen an:

```bash
choco pin list
```

- Hefte ein Paket in der installierten Version an:

```bash
choco pin add --name paket
```

- Hefte ein Paket in einer bestimmten Version an:

```bash
choco pin add --name paket --version version
```

- Entferne die Anheftung für ein bestimmtes Paket:

```bash
choco pin remove --name paket
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-pin: add German translation | 2020-10-13T00:10:19 | [ef571a6022e6](https://github.com/tldr-pages/tldr/commit/ef571a6022e6721104e07362b787401e0fb8b7ed)

