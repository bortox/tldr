---
author: ['bl-ue', 'Nicolas Kosinski', 'arnaudvalle', 'marchersimon']
date: 1633592259
title: "jest"
description: "jest, Une plateforme de test JavaScript sans configuration."
categories: "common"
---
> Plus d'informations : <https://jestjs.io>.

- Exécuter tous les tests disponibles :

```bash
jest
```

- Exécuter les suites de test de fichiers donnés :

```bash
jest chemin/vers/fichier1 chemin/vers/fichier2
```

- Exécuter les suites de test pour des fichiers, dans le répertoire courant et ses sous-répertoires, dont le chemin correspond à l'expression régulière indiquée :

```bash
jest expression_régulière expression_régulière
```

- Exécuter les tests dont les noms correspondent aux expressions régulières indiquées :

```bash
jest --testNamePattern nom_test
```

- Exécuter les suites de test associées à un fichier source donné :

```bash
jest --findRelatedTests chemin/vers/fichier_source.js
```

- Exécuter les suites de test associées à tous les fichiers non commités :

```bash
jest --onlyChanged
```

- Surveiller les changements sur les fichiers et ré-exécuter les tests associés :

```bash
jest --watch
```

- Montrer l'aide :

```bash
jest --help
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[arnaudvalle](mailto:arnaudvalle@users.noreply.github.com) | jest: add French translation (#4751) | 2020-10-19T19:59:57 | [3d7d037bbe07](https://github.com/tldr-pages/tldr/commit/3d7d037bbe0792d541be7b84b2b97bb0281f3779)

