---
author: ['CARE-COLIN Thibaut', 'bl-ue', 'Nicolas Kosinski', 'marchersimon']
date: 1633592259
title: "git bundle"
description: "git bundle, Empaquetez des objets et des références dans une archive."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-bundle>.

- Empaquetez tout les objets et les références d'une branche spécifiée :

```bash
git bundle create chemin/vers/fichier.bundle nom_de_branche
```

- Crée un empaquetage de tout les fichiers de toutes les branches :

```bash
git bundle create chemin/vers/fichier.bundle --all
```

- Crée un empaquetage des 5 derniers commits de la branche courante :

```bash
git bundle create chemin/vers/fichier.bundle -5 HEAD
```

- Crée un empaquetage des 7 derniers jours :

```bash
git bundle create chemin/vers/fichier.bundle --since=7.days HEAD
```

- Vérifie qu'un empaquetage est valide et peut être appliqué à la branche courante :

```bash
git bundle verify chemin/vers/fichier.bundle
```

- Affiche sur la sortie standard la liste des références contenues dans un empaquetage :

```bash
git bundle unbundle chemin/vers/fichier.bundle
```

- Extraire une branche spécifique d'un fichier de bundle dans le référentiel actuel :

```bash
git pull chemin/vers/fichier.bundle nom_de_branche
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

