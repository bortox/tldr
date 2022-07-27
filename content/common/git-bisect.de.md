---
author: ['marchersimon', 'DoPanik']
date: 1619262596
title: "git bisect, TLDR Pages"
description: "git bisect, Benuzt binäre Suche um den commit ausfindig zu machen, welcher einen Fehler beinhaltet."
categories: "common"
---
> Git springt im Commit-Graph automatisch vor und zurück, um den fehlerhaften Commit schrittweise einzugrenzen zu können.

> Weitere Informationen: <https://git-scm.com/docs/git-bisect>.

- Starte eine Bisect-Session in einem Commit-Bereich, der durch einen bekannten fehlerhaften Commit und einen sauberen Commit begrenzt wird:

```bash
git bisect start fehlerhafter_commit sauberer_commit
```

- Prüfe jeden Commit, den `git bisect` auswählt, und kennzeichne ihn mit "gut" oder "schlecht":

```bash
git bisect good|bad
```

- Wechsle zum vorherigen Branch zurück, nachdem der fehlerhafte Commit lokalisiert wurde:

```bash
git bisect reset
```

- Überspringe einen Commit während der Bisect-Session (z.B. einen, der die Tests aufgrund eines anderen Problems nicht bestanden hat):

```bash
git bisect skip
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-bisect: fix German translation | 2020-10-06T17:44:12 | [766024c4a5e4](https://github.com/tldr-pages/tldr/commit/766024c4a5e4ccebf772f32d0ebdc9391d9c7c57)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-bisect: add german translation | 2020-10-05T16:31:15 | [557660e181b8](https://github.com/tldr-pages/tldr/commit/557660e181b8410a7945404319209a52e6391417)

