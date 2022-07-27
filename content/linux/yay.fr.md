---
author: ['D34DPlayer', 'bl-ue', 'Nicolas Kosinski', 'Axel Navarro', 'marchersimon']
date: 1633592259
title: "yay, TLDR Pages"
description: "yay, Yet Another Yogurt : Un outil pour Arch Linux pour construire et installer des paquets depuis le Arch User Repository."
categories: "linux"
---
> À regarder : `pacman`.

> Plus d'informations : <https://github.com/Jguer/yay>.

- Recherche interactivement et installe des paquets depuis les dépôts et l'AUR :

```bash
yay nom_paquet|terme_recherche
```

- Synchronise et met à jour tous les paquets depuis les dépôts et l'AUR :

```bash
yay
```

- Synchronise et met à jour seulement les paquets de l'AUR :

```bash
yay -Sua
```

- Installe un nouveau paquet depuis les dépôts et l'AUR :

```bash
yay -S nom_paquet
```

- Recherche dans la base de données de paquets un mot clé depuis les dépôts et l'AUR :

```bash
yay -Ss mot_clé
```

- Montre des statistiques sur les paquets installés et la santé du système :

```bash
yay -Ps
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Axel Navarro](mailto:navarroaxel@gmail.com) | yay: add more information link (#5387) | 2021-03-08T21:16:15 | [16a149376348](https://github.com/tldr-pages/tldr/commit/16a149376348b5a91d473c9b064cd319727096b6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | yay: translate arguments and French typo | 2020-10-24T14:27:11 | [41ef81bcabdb](https://github.com/tldr-pages/tldr/commit/41ef81bcabdba187fade7e8f065c8458fc09c125)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | yay: add French translation | 2020-10-24T14:27:11 | [a6a2114c429f](https://github.com/tldr-pages/tldr/commit/a6a2114c429f916847725f9178604e585a1ab3e5)

