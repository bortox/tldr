---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco uninstall"
description: "choco uninstall, Deinstalliere mit Chocolatey ein oder mehrere Pakete."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-uninstall>.

- Deinstalliere ein oder mehrere Pakete, deren Namen mit Leerzeichen getrennt sind:

```bash
choco uninstall paket(e)
```

- Deinstalliere eine bestimmte Version eines Paketes:

```bash
choco uninstall paket --version version
```

- Stimme allen Fragen automatisch zu:

```bash
choco uninstall paket --yes
```

- Deinstalliere auch alle Abhängigkeiten:

```bash
choco uninstall paket --remove-dependencies
```

- Deinstalliere alle Pakete:

```bash
choco uninstall all
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-uninstall: add German translation | 2020-10-13T00:10:19 | [cd781c512536](https://github.com/tldr-pages/tldr/commit/cd781c51253684956fc35ab2156773d617e27e9e)

