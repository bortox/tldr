---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "git tag"
description: "git tag, Erstelle, lösche, überprüfe und liste Tags auf."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-tag>.

- Liste alle Tags auf:

```bash
git tag
```

- Erstelle einen Tag mit Namen, welcher auf den aktuellen Commit zeigt:

```bash
git tag tag_name
```

- Erstelle einen Tag mit Namen, welcher auf einen bestimmten Commit zeigt:

```bash
git tag tag_name commit
```

- Erstelle einen Tag mit Anmerkung:

```bash
git tag tag_name -m anmkerung
```

- Lösche einen Tag mit bestimmten Namen:

```bash
git tag -d tag_name
```

- Lade die aktualisierten Tags aus dem Upstream:

```bash
git fetch --tags
```

- Liste alle Tags auf, bei denen sich in den vorangegangenen Commits ein bestimmter Commit findet:

```bash
git tag --contains commit
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[LukBukkit](mailto:luk.bukkit@gmail.com) | git-tag: add German translation | 2020-10-24T14:39:05 | [6c83bf3e45c6](https://github.com/tldr-pages/tldr/commit/6c83bf3e45c693244c82487ea68782d8a8bdc687)

