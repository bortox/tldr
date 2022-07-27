---
author: ['MeerBiene', 'lincc']
date: 1643487459
title: "cp, TLDR Pages"
description: "cp, Kopiere Dateien und Verzeichnisse."
categories: "linux"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/cp>.

- Kopiere eine Datei an einen anderen Ort:

```bash
cp pfad/zur/ausgangs_datei.ext pfad/zur/ziel_datei.ext
```

- Kopiere eine Datei in ein anderes Verzeichnis und behalte den Dateinamen bei:

```bash
cp pfad/zur/ausgang_datei.ext pfad/zum/ziel_verzeichnis
```

- Kopiere die Inhalte eines Verzeichnisses rekursiv zu einem neuen Ort (wenn das Ziel existiert, wird das Verzeichnis ins bestehende Ziel Verzeichnis kopiert):

```bash
cp -r pfad/zum/ausgangs_verzeichnis pfad/zum/ziel_verzeichnis
```

- Kopiere ein Verzeichnis rekursiv im ausführlichen Modus (zeigt die Dateien die kopiert werden):

```bash
cp -vr pfad/zum/ausgangs_verzeichnis pfad/zum/ziel_verzeichnis
```

- Kopiere text Dateien zu einem anderen Ort im interaktiven Modus (fragt die Nutzer:in bevor eine Datei überschrieben wird):

```bash
cp -i *.txt pfad/zum/ziel_verzeichnis
```

- Folge symbolischen Verzeichnislinks vorm Kopieren:

```bash
cp -L link pfad/zum/ziel_verzeichnis
```

- Benutze den vollen Pfad der Ausgangsdateien und erstelle alle fehlenden Verzeichnisse beim Kopieren:

```bash
cp --parents quelle/pfad/zur/datei pfad/zur/ziel_datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[MeerBiene](mailto:60227302+MeerBiene@users.noreply.github.com) | linux/a*, cp: add German translation (#6777) | 2021-10-12T14:01:48 | [fb5e4b8305fa](https://github.com/tldr-pages/tldr/commit/fb5e4b8305fa484427d9923b102c25b2c2001efb)

