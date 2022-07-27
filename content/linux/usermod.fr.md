---
author: ['D34DPlayer', 'Patrice Denis', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "usermod, TLDR Pages"
description: "usermod, Modifie un compte utilisateur."
categories: "linux"
---
> Plus d'informations : <https://manned.org/usermod>.

- Change le nom d'un utilisateur :

```bash
usermod -l nouveau_nom utilisateur
```

- Ajoute l'utilisateur à des groupes supplémentaires (attention à l'omission d'espaces) :

```bash
usermod -a -G groupe1,groupe2 utilisateur
```

- Crée un nouveau dossier home pour un utilisateur et déplace ses fichiers vers celui-ci :

```bash
usermod -m -d /chemin/vers/home utilisateur
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[D34DPlayer](mailto:58138378+D34DPlayer@users.noreply.github.com) | usermod: French typos Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-24T14:27:11 | [84b0af700e01](https://github.com/tldr-pages/tldr/commit/84b0af700e01f9d37e41fe259b8115a7c604f3c9)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | usermod: translate arguments and French typo | 2020-10-24T14:27:11 | [d0e63b0ec5e4](https://github.com/tldr-pages/tldr/commit/d0e63b0ec5e47c2c0d678a4654609f92316005f2)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | usermod: add French translation | 2020-10-24T14:27:11 | [9ac0cc04cb44](https://github.com/tldr-pages/tldr/commit/9ac0cc04cb44ea0b468e9effab9711f74d08c56d)

