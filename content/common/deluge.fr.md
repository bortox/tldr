---
author: ['Ivor', 'Ivor Benderavage', 'bl-ue', 'marchersimon']
date: 1633592259
title: "deluge, TLDR Pages"
description: "deluge, Client BitTorrent à base de ligne de commande."
categories: "common"
---
> Plus d'informations : <https://deluge-torrent.org>.

- Télécharge un torrent :

```bash
deluge url|magnet|chemin/vers/fichier
```

- Télécharge un torrent à l'aide d'un fichier de configuration particulier :

```bash
deluge -c chemin/vers/fichier_configuration url|magnet|chemin/vers/fichier
```

- Télécharge un torrent et lance un interface usager particulier :

```bash
deluge -u gtk|web|console url|magnet|chemin/vers/fichier
```

- Télécharge un torrent et enregistre les journaux dans un ficher :

```bash
deluge -l chemin/vers/fichier_journalisation url|magnet|chemin/vers/fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | deluge: French translation formatting | 2020-12-30T14:23:22 | [c1c8c1bcf3ae](https://github.com/tldr-pages/tldr/commit/c1c8c1bcf3aec849f5999edd09cfbdecf832c260)
[Ivor](mailto:ivor.benderavage@gmail.com) | deluge: add French translation | 2020-12-30T14:23:22 | [aeeff8e77c72](https://github.com/tldr-pages/tldr/commit/aeeff8e77c72465d846b515db5e13e1f3c67e02b)

