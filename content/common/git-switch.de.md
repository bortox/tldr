---
author: ['LukBukkit', 'bl-ue', 'marchersimon']
date: 1619262596
title: "git switch"
description: "git switch, Wechsle zwischen Branches. Verfügbar ab Git Version 2.23+."
categories: "common"
---
> Siehe auch `git checkout`.

> Weitere Informationen: <https://git-scm.com/docs/git-switch>.

- Wechsle zu einem existierenden Branch:

```bash
git switch branche_name
```

- Erstelle einen neuen Branch und wechsele zu diesem:

```bash
git switch --create branch_name
```

- Erstelle einen neuen Branch basierend auf einem existierenden Commit und wechsele zu diesem:

```bash
git switch --create branch_name commit
```

- Wechsele zum vorherigen Branch:

```bash
git switch -
```

- Wechsele zu einem Branch und aktualisiere alle Submodule entsprechend:

```bash
git switch --recurse-submodules branch_name
```

- Wechsele zu einem Branch und merge automatisch den aktuellen Branch und alle Änderungen, die nicht committed wurden:

```bash
git switch --merge branch_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-switch: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [79b1257ea24f](https://github.com/tldr-pages/tldr/commit/79b1257ea24ff4293a7eca44482fa4eb6daf1a61)
[LukBukkit](mailto:luk.bukkit@gmail.com) | git-switch: add German translation | 2020-10-24T14:39:05 | [2c958f1ca999](https://github.com/tldr-pages/tldr/commit/2c958f1ca999479af2ca4517e7f8cbab0c3a2f3c)

