---
author: ['Patrice Denis', 'MarkusS', 'marchersimon']
date: 1619262596
title: "apt-add-repository, TLDR Pages"
description: "apt-add-repository, Editiere die Repository-Listen."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- Füge ein neues Repository hinzu:

```bash
apt-add-repository repository_spec
```

- Entferne ein Repository:

```bash
apt-add-repository --remove repository
```

- Aktualisiere den Cache nachdem das Repository hinzugefügt wurde:

```bash
apt-add-repository --update repository
```

- Aktiviere Source Pakete:

```bash
apt-add-repository --enable-source repository
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[MarkusS](mailto:markusscoding@outlook.com) | alpine, apt*, dnf, ip*: add German translation (#4707) | 2020-10-19T18:41:28 | [6e04e6dfc57e](https://github.com/tldr-pages/tldr/commit/6e04e6dfc57e323fed7b4ab2e5f46358463b2008)

