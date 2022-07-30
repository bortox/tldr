---
author: ['Nicolas Kosinski', 'D34DPlayer', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "iwctl"
description: "iwctl, Un outil de ligne de commande pour gérer iwd."
categories: "linux"
---
> Plus d'informations : <https://iwd.wiki.kernel.org/gettingstarted>.

- Lancer le mode interactif, dans ce mode vous pouvez entrer les commandes directement, avec de l'auto-complétion :

```bash
iwctl
```

- Avoir l'aide générale :

```bash
iwctl --help
```

- Afficher vos stations wifi :

```bash
iwctl station list
```

- Lancer la recherche de réseaux avec une station :

```bash
iwctl station station scan
```

- Afficher les réseaux trouvés par une station :

```bash
iwctl station station get-networks
```

- Se connecter à un réseau avec une station, si des informations de connexion sont nécessaires elles seront demandées :

```bash
iwctl station station connect nom_du_réseau
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[D34DPlayer](mailto:58138378+D34DPlayer@users.noreply.github.com) | iwctl: add page and French translation (#4594) | 2020-10-09T22:11:08 | [6c92ad98a9d5](https://github.com/tldr-pages/tldr/commit/6c92ad98a9d561cb4a0eb81336e648cd8e7e71f7)

