---
author: ['Ivor Benderavage', 'Dario Vladović', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "echo, TLDR Pages"
description: "echo, Affiche les paramètres donnés dans la console."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/echo>.

- Affiche un message (les guillemets sont facultatifs) :

```bash
echo "Hello World"
```

- Affiche un message avec des variables d'environnement :

```bash
echo "Ma variable PATH est $PATH"
```

- Affiche un message sans retour à la ligne :

```bash
echo -n "Hello World"
```

- Ajoute un message à un fichier :

```bash
echo "Hello World" >> fichier.txt
```

- Active l'interprétation des spécificateurs d'échappement :

```bash
echo -e "Colonne 1\tColonne 2"
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo: add link (#5606) | 2021-03-30T15:54:21 | [206703144d57](https://github.com/tldr-pages/tldr/commit/206703144d576491dbcf66be20770c47ebe329d3)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | mc, jekyll, echo: add French translation and fix formatting in English version (#5000) | 2020-12-03T13:11:40 | [2a56661112f9](https://github.com/tldr-pages/tldr/commit/2a56661112f929a3e49a51768ccc1e2a1ec1bf13)

