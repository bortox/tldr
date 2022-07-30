---
author: ['lucas schneider', 'Nicolas Kosinski', 'Antoine Amara', 'CARE-COLIN Thibaut', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "git describe"
description: "git describe, Créer un nom unique et lisible pour un objet à partir d'une référence disponible."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-describe>.

- Créer un nom unique pour le commit courant (le nom contient le tag le plus récent, le nombre de commits additionnels, et l'empreinte abrégée du commit) :

```bash
git describe
```

- Créer un nom avec une empreinte de commit de 4 caractères :

```bash
git describe --abbrev=4
```

- Générer un nom avec le chemin complet du tag :

```bash
git describe --all
```

- Décrire un tag Git :

```bash
git describe v1.0.0
```

- Créer un nom pour le dernier commit d'une branche donnée :

```bash
git describe nom_de_branche
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[Antoine Amara](mailto:amara.antoine@gmail.com) | git-describe: add French translation (#4724) | 2020-10-19T20:15:22 | [c448cf093d82](https://github.com/tldr-pages/tldr/commit/c448cf093d82eb21ab4bdcf76e55042bae355002)

