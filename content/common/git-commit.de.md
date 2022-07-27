---
author: ['Simon Marcher', 'DoPanik', 'Tan A', 'bl-ue', 'marchersimon']
date: 1626636503
title: "git commit, TLDR Pages"
description: "git commit, Committe Dateien in ein Repository."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-commit>.

- Committe gestagten Dateien zum Repository mit einer Nachricht:

```bash
git commit -m "nachricht"
```

- Committe alle gestagten Dateien zum Repository mit einer Nachricht aus einer Datei:

```bash
git commit --file pfad/zu/commit_nachricht_datei
```

- Stage alle modifizierten Dateien und committe sie mit einer Nachricht:

```bash
git commit -a -m "nachricht"
```

- Committe alle gestagten Dateien und [S]igniere sie mit dem in `~/.gitconfig` definierten GPG Schlüssel:

```bash
git commit -S -m "nachricht"
```

- Ersetze den letzten Commit mit den gerade auf dem Stage liegenden Änderungen:

```bash
git commit --amend
```

- Comitte nur spezifische Dateien (die Dateien müssen schon auf dem Stage liegen):

```bash
git commit pfad/zu/datei1 pfad/zu/datei2
```

- Erzeuge einen Commit, auch wenn keine Dateien auf dem Stage liegen:

```bash
git commit -m "nachricht" --allow-empty
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Simon Marcher](mailto:marchersimon@zohomail.eu) | git-commit: add gpg-sign example | 2021-07-18T21:28:23 | [155df72786a5](https://github.com/tldr-pages/tldr/commit/155df72786a50f53ed1b75684e39d5664c64872e)
[Simon Marcher](mailto:marchersimon@zohomail.eu) | git-commit: sync German translation | 2021-07-18T21:28:23 | [30e874052170](https://github.com/tldr-pages/tldr/commit/30e8740521700568abb3ecbc518b7253214920de)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-commit: quote message argument (#5477) | 2021-03-19T13:26:51 | [d526739418e8](https://github.com/tldr-pages/tldr/commit/d526739418e89eba9a32b3b6acfe406abb9bdb50)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-commit: add German translation | 2020-10-06T17:44:12 | [8bc28019c921](https://github.com/tldr-pages/tldr/commit/8bc28019c921cd0030089502c66bd752fa3d8376)

