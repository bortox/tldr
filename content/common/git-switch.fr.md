---
author: ['lucas schneider', 'Nicolas Kosinski', 'CARE-COLIN Thibaut', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git switch"
description: "git switch, Basculez entre les branches Git. Nécessite la version 2.23+ de Git."
categories: "common"
---
> Voir également `git checkout`.

> Plus d'informations : <https://git-scm.com/docs/git-switch>.

- Baculer sur une branche existante :

```bash
git switch nom_de_branche
```

- Créer une nouvelle branche et basculer dessus :

```bash
git switch --create nom_de_branche
```

- Créer une nouvelle branche en partant d'un commit donné et basculer dessus :

```bash
git switch --create nom_de_branche commit
```

- Basculer sur la branche précédente :

```bash
git switch -
```

- Basculer vers une branche et mettre à jour tous les sous-modules pour qu'ils correspondent :

```bash
git switch --recurse-submodules nom_de_branche
```

- Basculer vers une branche et fusionner automatiquement la branche actuelle et toutes les modifications non validées dedans :

```bash
git switch --merge nom_de_branche
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-switch: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [79b1257ea24f](https://github.com/tldr-pages/tldr/commit/79b1257ea24ff4293a7eca44482fa4eb6daf1a61)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

