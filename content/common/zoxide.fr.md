---
author: ['sebastientinel', 'bl-ue', 'Nicolas Kosinski', 'marchersimon']
date: 1633592259
title: "zoxide"
description: "zoxide, Garde une trace des répertoires les plus utilisés."
categories: "common"
---
> Utilise un algorithme de classement pour identifier le meilleur résultat.

> Plus d'informations : <https://github.com/ajeetdsouza/zoxide>.

- Aller au répertoire avec le meilleur classement qui contient "foo" dans son nom :

```bash
zoxide query foo
```

- Aller au répertoire avec le meilleur classement qui contient "foo" et "bar" dans son nom :

```bash
zoxide query foo bar
```

- Démarre une recherche de répertoire interactive (nécessite `fzf`) :

```bash
zoxide query --interactive
```

- Ajoute un répertoire ou incrémente son classement :

```bash
zoxide add chemin/du/répertoire
```

- Supprime un répertoire de la base de données de `zoxide` :

```bash
zoxide remove chemin/du/répertoire
```

- Génère la configuration du shell pour la mise en place des alias de commandes (`z`, `za`, `zi`, `zq`, `zr`) :

```bash
zoxide init bash|fish|zsh
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | z, zip, zless, zola, zopflipng, zoxide: add French translation (#4727) | 2020-10-19T19:04:15 | [ba78b756508c](https://github.com/tldr-pages/tldr/commit/ba78b756508c46ec6a44bd178b7f084fc2e50503)

