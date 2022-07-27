---
author: ['marchersimon', 'Ivor Benderavage', 'bl-ue', 'lincc']
date: 1643487459
title: "tput, TLDR Pages"
description: "tput, Accède et modifie les paramètres du terminal."
categories: "common"
---
> Plus d'informations : <https://manned.org/tput>.

- Déplace le curseur à un endroit donné sur l'écran :

```bash
tput cup coordonnée_y coordonnée_x
```

- Règle la couleur de l'avant-plan (af) ou de l'arrière-plan (ab) :

```bash
tput setaf|setab code_de_couleur_ANSI
```

- Affiche le numéro de colonnes, de rangées, ou de couleurs :

```bash
tput cols|lines|colors
```

- Active la sonnerie du terminal :

```bash
tput bel
```

- Réinitialise tous les attributs du terminal :

```bash
tput sgr0
```

- Active ou désactive le retour automatique à la ligne :

```bash
tput smam|rmam
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | which, tput, matlab: add French translation (#4943) | 2020-11-10T20:10:24 | [a0aeac1852b4](https://github.com/tldr-pages/tldr/commit/a0aeac1852b4f37e240b865702076bf6c029f705)

