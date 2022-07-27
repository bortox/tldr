---
author: ['marchersimon', 'DoPanik']
date: 1619262596
title: "git branch, TLDR Pages"
description: "git branch, Verwalte und Arbeite mit Git Branches."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-branch>.

- Liste alle lokalen Branches auf. Der momentan aktive (ausgecheckte) Branch wird mit `*` markiert:

```bash
git branch
```

- Liste alle Branches auf (Lokal und Remote):

```bash
git branch -a
```

- Zeige den Namen des aktuellen Branches:

```bash
git branch --show-current
```

- Erstelle einen neuen Branch auf Basis des letzten Commits:

```bash
git branch branch_name
```

- Erstelle einen neuen Branch auf Basis eines bestimmten Commits:

```bash
git branch branch_name commit_hash
```

- Benenne einen Branches um (der Branch muss nicht ausgecheckt sein):

```bash
git branch -m alter_branch_name neuer_branch_name
```

- Lösche einen lokalen Branch (der Branch muss nicht ausgecheckt sein):

```bash
git branch -d branch_name
```

- Lösche einen remote-Branch:

```bash
git push remote_name --delete remote_branch_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-branch: add German translation | 2020-10-06T17:44:12 | [d4fad2a2e34e](https://github.com/tldr-pages/tldr/commit/d4fad2a2e34e1c61a2ad6a175791cdfa1fbf1e68)

