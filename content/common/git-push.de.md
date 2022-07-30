---
author: ['bl-ue', 'DoPanik', 'Daniel', 'marchersimon']
date: 1634914980
title: "git push"
description: "git push, Lade Commits in ein Remote-Repository hoch."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-push>.

- Sende lokale Änderungen des aktuellen Branches zu seinem entfernten Repository (Remote Branch):

```bash
git push
```

- Sende lokale Änderungen des angegebenen Branches zu seinem entfernten Repository:

```bash
git push remote_name lokaler_branch
```

- Lade den aktuellen Branch in ein entferntes Repository mit Angabe des Namens des entfernten Branches hoch:

```bash
git push remote_name -u remote_branch
```

- Lade Änderungen aller lokalen Branches zu ihrem entfernten Repository hoch:

```bash
git push --all remote_name
```

- Lösche einen Branch in einem entfernten Repository:

```bash
git push remote_name --delete remote_branch
```

- Entferne alle remote Branches, welche kein lokales Gegenstück besitzen:

```bash
git push --prune remote_name
```

- Veröffentliche Tags, welche noch nicht im entfernten Repository vorhanden sind:

```bash
git push --tags
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | German pages: fix (valid) tldr-lint errors (#5363) | 2021-03-08T20:38:36 | [22ac7d5e0e34](https://github.com/tldr-pages/tldr/commit/22ac7d5e0e34bac2d1640ba3505be55eeabb2773)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-push: add German translation | 2020-10-06T17:44:12 | [42488492b727](https://github.com/tldr-pages/tldr/commit/42488492b727acf70a8e0ff04c2a34e260ed152b)

