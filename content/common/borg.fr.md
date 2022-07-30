---
author: ['David Bariod', 'Nicolas Kosinski', 'julien', 'bl-ue', 'marchersimon']
date: 1633592259
title: "borg"
description: "borg, Outil de sauvegarde avec dé-duplication."
categories: "common"
---
> Crée des sauvegardes distantes ou locales qui peuvent être montées comme un système de fichiers.

> Plus d'informations : <https://borgbackup.readthedocs.io/en/stable/usage/general.html>.

- Initialise un dépôt local :

```bash
borg init /chemin/vers/repertoire_du_depot
```

- Sauvegarde un répertoire dans le dépôt en créant une archive appelée "Lundi" :

```bash
borg create --progress /chemin/vers/repertoire_du_depot::Lundi /chemin/vers/repertoire_source
```

- Liste toutes les archives d'un dépôt :

```bash
borg list /chemin/vers/repertoire_du_depot
```

- Extrait un répertoire donné de l'archive nommée "Lundi" à partir d'un dépôt distant tout en excluant tous les fichiers *.ext :

```bash
borg extract utilisateur@hote:/chemin/vers/repertoire_du_depot::Lundi chemin/vers/repertoire_destination --exclude '*.ext'
```

- Nettoie un dépôt en effaçant toutes les archives âgées de plus de 7 jours tout en affichant les changements :

```bash
borg prune --keep-within 7d --list /chemin/vers/repertoire_du_depot
```

- Monte un dépôt comme un système de fichiers FUSE :

```bash
borg mount /chemin/vers/repertoire_du_depot::Lundi /chemin/vers/point_de_montage
```

- Affiche l'aide sur la création d'archives :

```bash
borg create --help
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | borg: reworded header for French translation | 2019-10-26T17:59:51 | [598e6730e382](https://github.com/tldr-pages/tldr/commit/598e6730e3826b31e8f245ce7fdc81b2423029de)
[julien](mailto:git@julienc.io) | borg: fix French punctuation | 2019-10-26T17:59:51 | [f86a83c9d3b1](https://github.com/tldr-pages/tldr/commit/f86a83c9d3b17dd80e69892843088fc1be822db7)
[David Bariod](mailto:davidriod@googlemail.com) | borg: add French translation (#3160) | 2019-07-09T18:05:43 | [a2f1b2bdb889](https://github.com/tldr-pages/tldr/commit/a2f1b2bdb889dc862d07e5917f63214a1ee950bb)

