---
author: ['Felix Brilej', 'bl-ue', 'marchersimon']
date: 1623709650
title: "emacsclient, TLDR Pages"
description: "emacsclient, Öffnet Dateien in einem laufenden Emacs-Server."
categories: "common"
---
> Siehe auch `emacs`.

> Weitere Informationen: <https://www.emacswiki.org/emacs/EmacsClient>.

- Öffne eine Datei in einem laufenden Emacs-Server (mit GUI wenn möglich):

```bash
emacsclient pfad/zu/datei
```

- Öffne eine Datei in der Konsole (ohne X-Fenster):

```bash
emacsclient --no-window-system pfad/zu/datei
```

- Öffne eine Datei in einem neuen Emacs Fenster:

```bash
emacsclient --create-frame pfad/zu/datei
```

- Führe einen Befehl aus und schreibe das Ergebnis in stdout:

```bash
emacsclient --eval '(befehl)'
```

- Gib einen alternativen Editor an für den Fall, dass kein Emacs-Server läuft:

```bash
emacsclient --alternate-editor editor pfad/zu/datei
```

- Beende einen laufenden Emacs-Server und alle Instanzen und frage nach Bestätigung für ungespeicherte Dateien:

```bash
emacsclient --eval '(save-buffers-kill-emacs)'
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | emacs, emacsclient: refresh (#6096) | 2021-06-15T00:27:30 | [68023b7eb89b](https://github.com/tldr-pages/tldr/commit/68023b7eb89b7a2897d19fb6ecad7fe6a1e96eb9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | emacs*: add German translation (#4828) | 2020-10-24T16:25:53 | [752392dfa532](https://github.com/tldr-pages/tldr/commit/752392dfa532e2566ff61a62898b87848ab0ed3e)

