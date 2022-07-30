---
author: ['marchersimon']
date: 1619262596
title: "aapt"
description: "aapt, Android Asset Packaging Tool."
categories: "common"
---
> Kompiliere und verpacke die Resourcen einer Android App.

> Weitere Informationen: <https://elinux.org/Android_aapt>.

- Liste alle Dateien eines APK Archivs auf:

```bash
aapt list pfad/zu/app.apk
```

- Zeige die Metadaten einer App an (Version, Berechtigungen, usw.):

```bash
aapt dump badging pfad/zu/app.apk
```

- Erstelle ein neues APK Archiv mit den Dateien eines bestimmten Verzeichnisses:

```bash
aapt package -F pfad/zu/app.apk pfad/zu/verzeichnis
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

