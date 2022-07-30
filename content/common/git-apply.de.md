---
author: ['DoPanik', 'marchersimon']
date: 1619893215
title: "git apply"
description: "git apply, Integriere eine Patch-Datei und/oder füge sie zum Index hinzu."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-apply>.

- Gib Informationen über gepatchte Dateien aus:

```bash
git apply --verbose pfad/zu/datei
```

- Integriere die Patch-Datei und füge sie zum Index hinzu:

```bash
git apply --index pfad/zu/datei
```

- Integriere eine externe Patch-Datei:

```bash
curl https://beispiel.de/datei.patch | git apply
```

- Gib diffstat des Inputs aus und integriere die Patch-Datei:

```bash
git apply --stat --apply pfad/zu/datei
```

- Integriere eine Patch-Datei in umgekehrter Reihenfolge:

```bash
git apply --reverse pfad/zu/datei
```

- Speichere das Ergebnis einer Patch-Datei im Index, ohne den Arbeitsbaum zu verändern:

```bash
git apply --cache pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-apply: add german translation | 2020-10-05T16:31:15 | [61dc7a5e0fa0](https://github.com/tldr-pages/tldr/commit/61dc7a5e0fa0cd93aae6b85ff2d67fd18cad7900)

