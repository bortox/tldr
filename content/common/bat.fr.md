---
author: ['Hugo', 'ferrvic', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "bat, TLDR Pages"
description: "bat, Affiche et concatène le contenu d'un ou plusieurs fichiers."
categories: "common"
---
> Un clone de `cat` avec mise en valeur de la syntaxe et intégration avec Git.

> Plus d'informations : <https://github.com/sharkdp/bat>.

- Affiche le contenu d'un fichier sur la sortie standard :

```bash
bat fichier
```

- Concatène le contenu de plusieurs fichiers vers le fichier de destination :

```bash
bat fichier1 fichier2 > fichier_de_destination
```

- Ajoute le contenu d'un ficher à la fin du fichier de destination :

```bash
bat fichier1 fichier2 >> fichier_de_destination
```

- Numérote toutes les lignes affichées :

```bash
bat -n fichier
```

- Affiche le contenu d'un fichier JSON sur la sortie standard avec mise en valeur de la syntaxe :

```bash
bat --language json fichier.json
```

- Affiche tous les langages pris en charge :

```bash
bat --list-languages
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Hugo](mailto:60650748+TaoHuaLiu@users.noreply.github.com) | bat: fix typos (#5822) | 2021-04-23T14:58:36 | [6a037d6fdbb9](https://github.com/tldr-pages/tldr/commit/6a037d6fdbb91bf695d50b8bfacd752e8ca95a46)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[ferrvic](mailto:73243127+ferrvic@users.noreply.github.com) | bat: add french language (#4798) | 2020-10-24T14:48:55 | [cc0d65b302b7](https://github.com/tldr-pages/tldr/commit/cc0d65b302b7b8ca39a318cb9bd9365c95bf96c4)

