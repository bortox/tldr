---
author: ['Dario Vladović', 'marchersimon', 'Pascal Iske']
date: 1619893215
title: "cp, TLDR Pages"
description: "cp, Kopiere Dateien und Verzeichnisse."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/cp>.

- Kopiere eine Datei an einen anderen Ort:

```bash
cp pfad/zu/datei pfad/zu/kopie
```

- Kopiere eine Datei an einen anderen Ort und behalte den Dateinamen:

```bash
cp pfad/zu/datei pfad/zu/zielverzeichnis
```

- Kopiere ein Verzeichnis rekursiv (falls der Zielort bereits existiert, wird das Verzeichnis in das Zielverzeichnis kopiert):

```bash
cp -r pfad/zu/verzeichnis pfad/zu/zielverzeichnis
```

- Kopiere ein Verzeichnis rekursiv und gib alle Dateien aus, während sie kopiert werden:

```bash
cp -vr pfad/zu/verzeichnis pfad/zu/zielverzeichnis
```

- Kopiere alle Textdateien in einem Verzeichnis und warte auf eine Bestätigung, falls eine Datei überschrieben werden soll:

```bash
cp -i /pfad/zu/*.txt pfad/zu/zielverzeichnis
```

- Folge symbolischen Links vor dem Kopieren:

```bash
cp -L link pfad/zu/zielverzeichnis
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Pascal Iske](mailto:info@pascal-iske.de) | cp: add german translation | 2019-11-02T18:52:30 | [e76be2b3a941](https://github.com/tldr-pages/tldr/commit/e76be2b3a941a788a2505f71e5d424126cebb0b9)

