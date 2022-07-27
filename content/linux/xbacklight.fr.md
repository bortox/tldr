---
author: ['D34DPlayer', 'bl-ue', 'marchersimon']
date: 1633592259
title: "xbacklight, TLDR Pages"
description: "xbacklight, Outil pour ajuster la luminosité du rétroéclairage en utilisant l'extension RandR."
categories: "linux"
---
> Plus d'informations : <https://gitlab.freedesktop.org/xorg/app/xbacklight>.

- Obtient le niveau de luminosité de l'écran actuel comme un pourcentage :

```bash
xbacklight
```

- Régle la luminosité de l'écran à 40% :

```bash
xbacklight -set 40
```

- Augmente la luminosité de l'écran actuel de 25% :

```bash
xbacklight -inc 25
```

- Diminue la luminosité de l'écran actuel de 75% :

```bash
xbacklight -dec 75
```

- Augment la luminosité de l'écran à 100%, étendu sur 60 secondes (valeur donnée en ms), en 60 pas :

```bash
xbacklight -set 100 -time 60000 -steps 60
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | xbacklight: translate arguments and French typo | 2020-10-24T14:27:11 | [de2b9b0dc57c](https://github.com/tldr-pages/tldr/commit/de2b9b0dc57ca2ab8d02f6997a31a3de31c3565a)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | xbacklight: add French translation | 2020-10-24T14:27:11 | [e3eb2aa8424c](https://github.com/tldr-pages/tldr/commit/e3eb2aa8424cd4c7fbcc73e427687aeb50e61ed6)

