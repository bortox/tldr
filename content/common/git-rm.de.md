---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "git rm, TLDR Pages"
description: "git rm, Entferne Dateien aus dem Index des Repositories und vom lokalen Dateisystem."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-rm>.

- Entferne eine Datei aus dem Index und vom lokalen Dateisystem:

```bash
git rm pfad/zu/datei
```

- Entferne ein Verzeichnis:

```bash
git rm -r pfad/zu/verzeichnis
```

- Entferne eine Datei aus dem Index des Repositories, aber behalte sie lokal:

```bash
git rm --cached pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[LukBukkit](mailto:luk.bukkit@gmail.com) | git-rm: add German translation | 2020-10-24T14:39:05 | [b2ce57d39901](https://github.com/tldr-pages/tldr/commit/b2ce57d3990111385e6c363c6681471a47560a06)

