---
author: ['D34DPlayer', 'Nicolas Hansse', 'bl-ue', 'Axel Navarro', 'marchersimon']
date: 1635127833
title: "pacman, TLDR Pages"
description: "pacman, Outil de gestion de paquets sur Arch Linux."
categories: "linux"
---
> Certaines commandes comme `pacman sync` ont leur propre documentation.

> Plus d'informations : <https://man.archlinux.org/man/pacman.8>.

- Synchronise et mets à jour tous les paquets :

```bash
sudo pacman --sync --refresh --sysupgrade
```

- Installe un nouveau paquet :

```bash
sudo pacman --sync nom_paquet
```

- Efface un paquet et ses dépendances :

```bash
sudo pacman --remove --recursive nom_paquet
```

- Recherche dans la base de données des paquets une expression régulière ou mot clé :

```bash
pacman --sync --search "terme_recherche"
```

- Liste les paquets installés et leurs versions :

```bash
pacman --query
```

- Liste seulement les paquets installés explicitement et leurs versions :

```bash
pacman --query --explicit
```

- Trouve à quel paquet un certain fichier appartient :

```bash
pacman --query --owns fichier
```

- Vide le cache des paquets pour libérer de l'espace :

```bash
sudo pacman --sync --clean --clean
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pacman: add sudo and use long options (#7132) | 2021-10-25T04:10:33 | [c9b534415099](https://github.com/tldr-pages/tldr/commit/c9b534415099cd2931eaf120938f201240c521a8)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | *: mention subcommands in FR translations (#6823) | 2021-10-06T22:45:59 | [b0e0a6e58cfb](https://github.com/tldr-pages/tldr/commit/b0e0a6e58cfbff6cb7041a4d37b1b46ddac79941)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman: add more information link (#5146) | 2021-01-19T15:40:16 | [dbb0e9ef9767](https://github.com/tldr-pages/tldr/commit/dbb0e9ef97671aff87d987e2e67dce8f19d6668a)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | pacman: translate arguments and French typo | 2020-10-24T14:27:11 | [e3892ce25aad](https://github.com/tldr-pages/tldr/commit/e3892ce25aadd19b8907197ba2328be6d5fee89e)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | pacman: add French translation | 2020-10-24T14:27:11 | [fb67f211039e](https://github.com/tldr-pages/tldr/commit/fb67f211039eade0fd012d790a7612a0852f2761)

