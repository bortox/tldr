---
author: ['Frank Benedikt', 'bl-ue', 'Daniel', 'marchersimon']
date: 1634914980
title: "convert"
description: "convert, ImageMagick Bildkonvertierungswerkzeug."
categories: "common"
---
> Weitere Informationen: <https://imagemagick.org/script/convert.php>.

- Konvertiere ein Bild von JPG nach PNG:

```bash
convert pfad/zu/bild.jpg pfad/zu/bild.png
```

- Skaliere ein Bild auf 50% seiner Originalgröße:

```bash
convert pfad/zu/bild.png -resize 50% pfad/zu/bild2.png
```

- Skaliere ein Bild unter Beibehaltung des ursprünglichen Seitenverhältnisses auf eine maximale Größe von 640x480:

```bash
convert pfad/zu/bild.png -resize 640x480 pfad/zu/bild2.png
```

- Hänge Bilder horizontal aneinander:

```bash
convert pfad/zu/bild1.png pfad/zu/bild2.png pfad/zu/bild3.png +append pfad/zu/bild123.png
```

- Hänge Bilder vertikal aneinander:

```bash
convert pfad/zu/bild1.png pfad/zu/bild2.png pfad/zu/bild3.png -append pfad/zu/bild123.png
```

- Erstelle ein animiertes GIF aus einer Serie von Bildern mit einer Verzögerung von 100 ms zwischen den Bildern:

```bash
convert pfad/zu/bild1.png pfad/zu/bild2.png pfad/zu/bild3.png -delay 10 pfad/zu/animation.gif
```

- Erstelle ein Bild mit nichts als einem festen Hintergrund:

```bash
convert -size 800x600 "xc:#ff0000" pfad/zu/bild.png
```

- Erstelle ein Favicon aus mehreren Bildern verschiedener Größe:

```bash
convert pfad/zu/bild1.png pfad/zu/bild2.png pfad/zu/bild3.png pfad/zu/bild.ico
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | German pages: fix (valid) tldr-lint errors (#5363) | 2021-03-08T20:38:36 | [22ac7d5e0e34](https://github.com/tldr-pages/tldr/commit/22ac7d5e0e34bac2d1640ba3505be55eeabb2773)
[Frank Benedikt](mailto:63481435+FrankBG67@users.noreply.github.com) | German translation: alias, bash, borg, cd, chmod, chromium, chsh, convert, exa (#4132) Co-authored-by: Zlatan Vasović [...] | 2020-06-29T23:59:34 | [9aa5907281cb](https://github.com/tldr-pages/tldr/commit/9aa5907281cbaa7a0ee08b5c330c660d779282c7)

