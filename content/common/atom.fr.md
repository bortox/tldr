---
author: ['Nicolas Kosinski', 'bl-ue', 'marchersimon', 'julien']
date: 1633592259
title: "atom, TLDR Pages"
description: "atom, Un éditeur de texte multiplateforme proposant de nombreuses extensions."
categories: "common"
---
> Les extensions sont gérées par `apm`.

> Plus d'informations : <https://atom.io/>.

- Ouvrir un fichier ou un dossier :

```bash
atom chemin/vers/fichier_ou_dossier
```

- Ouvrir un fichier ou un dossier dans une nouvelle fenêtre :

```bash
atom -n chemin/vers/fichier_ou_dossier
```

- Ouvrir un fichier ou un dossier dans une fenêtre existante :

```bash
atom --add chemin/vers/fichier_ou_dossier
```

- Ouvrir en mode sans-échec (les extensions ne seront pas chargées) :

```bash
atom --safe
```

- Empêcher Atom de se lancer en arrière-plan, en le forçant à s'attacher au terminal :

```bash
atom --foreground
```

- Attendre la fermeture de la fenêtre avant de quitter (utile pour l'éditeur de commits Git) :

```bash
atom --wait
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | atom, clear, convert, df: sync French translations with English pages (#5797) | 2021-04-20T20:15:58 | [df7770ae6b58](https://github.com/tldr-pages/tldr/commit/df7770ae6b585a043f7a797de941a1c425acc6a5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | atom: add French translation | 2019-10-27T17:33:39 | [f85051360c17](https://github.com/tldr-pages/tldr/commit/f85051360c1775934dabc0d7176f04addc1367c6)

