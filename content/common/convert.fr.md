---
author: ['julien', 'bl-ue', 'Nicolas Kosinski', 'marchersimon']
date: 1633592259
title: "convert"
description: "convert, Outil de conversion d'image d'ImageMagick."
categories: "common"
---
> Plus d'informations : <https://imagemagick.org/script/convert.php>.

- Convertir une image JPG en PNG :

```bash
convert image.jpg image.png
```

- Redimensionner une image à 50% de ses dimensions d'origine :

```bash
convert image.png -resize 50% image2.png
```

- Redimensionner une image en conservant son ratio hauteur/largeur initial pour une taille maximum de 640x480 :

```bash
convert image.png -resize 640x480 image2.png
```

- Coller plusieurs images horizontallement :

```bash
convert image1.png image2.png image3.png +append image123.png
```

- Coller plusieurs images verticalement :

```bash
convert image1.png image2.png image3.png -append image123.png
```

- Créer un gif à partir d'une série d'images avec un délai de 100ms entre chaque :

```bash
convert image1.png image2.png image3.png -delay 100 animation.gif
```

- Créer une image avec un simple arrière-plan uni :

```bash
convert -size 800x600 "xc:#ff0000" image.png
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | atom, clear, convert, df: sync French translations with English pages (#5797) | 2021-04-20T20:15:58 | [df7770ae6b58](https://github.com/tldr-pages/tldr/commit/df7770ae6b585a043f7a797de941a1c425acc6a5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | convert: add French translation | 2019-10-27T17:33:39 | [92ef3cd0077b](https://github.com/tldr-pages/tldr/commit/92ef3cd0077b6fe251af4393f33b585eb36d5da2)

