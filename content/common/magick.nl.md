---
author: ['Jennifer']
date: 1602536630
title: "magick"
description: "magick, Creër, bewerk, vorm, of converteer bitmapafbeeldingen."
categories: "common"
---
> ImageMagick versie 7+. Bekijk `convert` versies 6 en lager.

> Meer informatie: <https://imagemagick.org/>.

- Converteer bestandstype:

```bash
magick afbeelding.png afbeelding.jpg
```

- Formaat van een afbeelding wijzigen, maak een nieuw kopie:

```bash
magick convert -resize 100x100 afbeelding.jpg afbeelding.jpg
```

- Creër een GIF door middel van afbeeldingen:

```bash
magick *.jpg afbeelding.gif
```

- Creër een dambordpatroon:

```bash
magick -size 640x480 pattern:checkerboard dambordpatroon.png
```

- Converteer afbeeldingen naar individuele PDF-pagina's:

```bash
magick *.jpg +adjoin pagina-%d.pdf
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Jennifer](mailto:42771751+JenniX3@users.noreply.github.com) | magick: add Dutch translation (#4612) | 2020-10-12T23:03:50 | [c4cf48e9222d](https://github.com/tldr-pages/tldr/commit/c4cf48e9222d043ab6724f2e2b460b45e068e287)

