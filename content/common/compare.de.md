---
author: ['marchersimon']
date: 1619262596
title: "compare, TLDR Pages"
description: "compare, Zeige Unterschiede von zwei Bildern."
categories: "common"
---
> Weitere Informationen: <https://imagemagick.org/script/compare.php>.

- Vergleiche 2 Bilder:

```bash
compare pfad/zu/bild1.png pfad/zu/bild2.png pfad/zu/diff.png
```

- Vergleiche 2 Bilder mit einer bestimmten Metrik (standardmäßig NCC):

```bash
compare -verbose -metric PSNR pfad/zu/bild1.png pfad/zu/bild2.png pfad/zu/diff.png
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

