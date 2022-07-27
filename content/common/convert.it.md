---
author: ['Marco Bonelli']
date: 1560123302
title: "convert, TLDR Pages"
description: "convert, Strumento della suite immagineMagick per la conversione di immagini."
categories: "common"
---
> Maggiori informazioni: <https://imagemagick.org/script/convert.php>.

- Converti un'immagine da JPG a PNG:

```bash
convert immagine.jpg immagine.png
```

- Scala un'immagine al 50% delle sue dimensioni originali:

```bash
convert immagine.png -resize 50% immagine2.png
```

- Scala un'immagine ad una dimensione massima di 640x480 mantenendo le proporzioni originali:

```bash
convert immagine.png -resize 640x480 immagine2.png
```

- Concatena più immagini orizzontalmente:

```bash
convert immagine1.png immagine2.png immagine3.png +append immagine123.png
```

- Crea una GIF da una serie di immagini con un intervallo di 100ms tra ogni immagine:

```bash
convert immagine1.png immagine2.png immagine3.png -delay 100 animazione.gif
```

- Crea un'immagine a tinta unita di un determinato colore:

```bash
convert -size 800x600 "xc:#ff0000" immagine.png
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | convert: add Italian translation. | 2019-06-10T01:35:02 | [95abcefda372](https://github.com/tldr-pages/tldr/commit/95abcefda372cd323c76437ee5a906c4526296e0)

