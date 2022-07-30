---
author: ['bl-ue', 'marchersimon', 'D34DPlayer', 'Nicolas Kosinski']
date: 1659075216
title: "xclip, TLDR Pages"
description: "xclip, Outil de manipulation de presse-papiers X11, semblable à `xsel`."
categories: "linux"
---
> Gère les sélections primaires et secondaires de X, en plus du presse-papier système (`Ctrl + C`/`Ctrl + V`).

> Plus d'informations : <https://manned.org/xclip>.

- Copie la sortie d'une commande vers la zone de sélection primaire de X11 (presse-papiers) :

```bash
echo 123 | xclip
```

- Copie la sortie d'une commande vers une zone de sélection de X11 donnée :

```bash
echo 123 | xclip -selection primary|secondary|clipboard
```

- Copie le contenu d'un fichier vers le presse-papiers système, avec la notation courte :

```bash
echo 123 | xclip -sel clip
```

- Copie le contenu d'un fichier vers le presse-papiers système :

```bash
xclip -sel clip fichier_entrée.txt
```

- Copie le contenu d'une image PNG vers le presse-papiers système (peut être collé dans d'autres programmes correctement) :

```bash
xclip -sel clip -t image/png fichier_entrée.png
```

- Colle le contenu de la zone de sélection de X11 à la console :

```bash
xclip -o
```

- Colle le contenu du presse-papier système à la console :

```bash
xclip -o -sel clip
```

- Colle le contenu du presse-papier système à un fichier :

```bash
xclip -o -sel clip > fichier_sortie.txt
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | xclip: translate arguments and French typo | 2020-10-24T14:27:11 | [38b10f223998](https://github.com/tldr-pages/tldr/commit/38b10f2239988cda3ab349be763c6869480c1a14)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | xclip: add French translation | 2020-10-24T14:27:11 | [e5aff32fbb70](https://github.com/tldr-pages/tldr/commit/e5aff32fbb70d2be4a11b18c82f40de1b884534b)

