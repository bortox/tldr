---
author: ['CARE-COLIN Thibaut', 'bl-ue', 'lucas schneider', 'marchersimon']
date: 1633592259
title: "git lfs"
description: "git lfs, Travailler dans un registre Git avec des fichiers volumineux."
categories: "common"
---
> Plus d'informations : <https://git-lfs.github.com>.

- Initialise le Git LFS :

```bash
git lfs install
```

- Suivre des fichiers correspondant à un pattern :

```bash
git lfs track '*.bin'
```

- Changer l'URL du point de terminaison Git LFS (utile si le serveur LFS est séparé du serveur Git) :

```bash
git config -f .lfsconfig lfs.url lfs_endpoint_url
```

- Lister les pattern de fichiers suivis :

```bash
git lfs track
```

- Lister les fichiers suivis ayant été commité :

```bash
git lfs ls-files
```

- Pousser tout les objets LFS vers le serveur distant :

```bash
git lfs push --all nom_distant nom_de_branche
```

- Chercher tout les objets LFS :

```bash
git lfs fetch
```

- Charger tout les objets LFS :

```bash
git lfs checkout
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

