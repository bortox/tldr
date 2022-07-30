---
author: ['DoPanik', 'marchersimon']
date: 1619262596
title: "git archive"
description: "git archive, Erstelle ein Archiv von Dateien."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-archive>.

- Erstelle ein tar-Archiv aus dem Inhalt des aktuellen HEAD und gib dieses aus:

```bash
git archive --verbose HEAD
```

- Erstelle ein zip-Archiv aus dem Inhalt des aktuellen HEAD und gib dieses aus:

```bash
git archive --verbose --format=zip HEAD
```

- Erstelle ein zip-Archiv aus dem Inhalt des aktuellen HEAD und speichere dieses in eine Datei:

```bash
git archive --verbose --output=pfad/zu/datei.zip HEAD
```

- Erstelle ein tar-Archiv aus dem Inhalt des letzten Commits eines bestimmten Branches:

```bash
git archive --output=pfad/zu/datei.tar branch_name
```

- Erstelle ein tar-Archiv aus dem Inhalt eines bestimmten Verzeichnisses:

```bash
git archive --output=pfad/zu/datei.tar HEAD:pfad/zu/verzeichnis
```

- Stelle jeder Datei einen Pfad voran, um sie in einem bestimmten Verzeichnis zu archivieren:

```bash
git archive --output=pfad/zu/datei.tar --prefix=pfad/zu/verzeichnis/ HEAD
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[DoPanik](mailto:963151+DoPaNik@users.noreply.github.com) | git-archive: add german translation | 2020-10-05T16:31:15 | [69359c60ff37](https://github.com/tldr-pages/tldr/commit/69359c60ff37dda810402a06364c31f60d77a1a6)

