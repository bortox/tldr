---
author: ['Simon Landry', 'Patrice Denis', 'CARE-COLIN Thibaut', 'lucas schneider', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git reset, TLDR Pages"
description: "git reset, Enlève des commits ou des changements en réinitialisant la tête Git à l'état spécifié."
categories: "common"
---
> Si un chemin est passé en paramètre, Git reset fonctionne comme «unstage».

> Si un hash de commit est passé en paramètre, Git reset annule les commits jusqu'à ce dernier.

> Plus d'informations : <https://git-scm.com/docs/git-reset>.

- Tout enlever de la *zone de stage* :

```bash
git reset
```

- Enlever des fichiers spécifiques de la *zone de stage* :

```bash
git reset chemin/vers/fichier(s)
```

- Enlever, en mode interactif, des fichiers spécifiques de l’index :

```bash
git reset --patch chemin/vers/fichier
```

- Annuler le dernier *commit*, mais garder les changements effectués dans votre système de fichiers :

```bash
git reset HEAD~
```

- Défaire les deux derniers *commits*, et ajouter leurs changements à l'index (dans la zone de stage) :

```bash
git reset --soft HEAD~2
```

- Enlever tout les changements qui n'ont pas été *commit*, qu'ils soient dans la *zone de stage* ou non (pour enlever seulement les changements de la *zone de stage*, utiliser `git checkout`) :

```bash
git reset --hard
```

- Réinitialiser le dépôt à un commit spécifique en retirant tout les changements (ceci inclus les changements dans des commits entre la *tête* et le *commit* spécifié !) :

```bash
git reset --hard commit
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | git-reset: clarify patch example and use long option (#6006) | 2021-05-28T13:30:39 | [9fe15f560944](https://github.com/tldr-pages/tldr/commit/9fe15f560944e421629b70d2e1979f65a569036b)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[Simon Landry](mailto:landry_simon@pm.me) | git-reset: add French translation (#4621) | 2020-10-11T05:34:04 | [28e90fbb75e0](https://github.com/tldr-pages/tldr/commit/28e90fbb75e014a9743e31c00364fd4bfea1abe6)

