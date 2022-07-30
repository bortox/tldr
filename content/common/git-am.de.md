---
author: ['DoPanik', 'marchersimon']
date: 1619262596
title: "git am"
description: "git am, Patch-Dateien integrieren. Nützlich beim Empfang von Commits per E-Mail."
categories: "common"
---
> Siehe auch `git format-patch` zur Erzeugung von Patch-Dateien.

> Weitere Informationen: <https://git-scm.com/docs/git-am>.

- Integriere eine Patch-Datei:

```bash
git am pfad/zu/datei.patch
```

- Brich das Integrieren einer Patch-Datei ab:

```bash
git am --abort
```

- Integriere so viele Patch-Dateien wie möglich und speichere fehlgeschlagene Teile:

```bash
git am --reject pfad/zu/datei.patch
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-am: add german translation | 2020-10-05T16:31:15 | [e5a515c33ee2](https://github.com/tldr-pages/tldr/commit/e5a515c33ee27c5def3e0d263c39d4768be50555)

