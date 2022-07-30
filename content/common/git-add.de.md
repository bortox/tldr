---
author: ['bl-ue', 'Lucas Gabriel Schneider', 'DoPanik', 'marchersimon']
date: 1619893215
title: "git add"
description: "git add, Füge Dateien zum Index/Stage hinzu."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-add>.

- Füge eine bestimmte Datei zum Index hinzu:

```bash
git add pfad/zu/datei
```

- Füge alle Dateien zum Index hinzu (nachverfolgte und nicht nachverfolgte):

```bash
git add -A
```

- Füge nur nachverfolgte Dateien zum Index hinzu (Updaten des Index):

```bash
git add -u
```

- Füge auch Dateien, welche ignoriert werden (`.gitignore`) hinzu:

```bash
git add -f
```

- Füge Teile von Dateien zum Index interaktiv hinzu:

```bash
git add -p
```

- Füge Teile einer bestimmten Datei interaktiv hinzu:

```bash
git add -p pfad/zu/datei
```

- Füge Dateien zum Index interaktiv hinzu:

```bash
git add -i
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-add: add german translation | 2020-10-05T16:31:15 | [41d31bc7b906](https://github.com/tldr-pages/tldr/commit/41d31bc7b90602c0367ce51403234aecd9fb6db2)

