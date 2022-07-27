---
author: ['Nicolas Hansse']
date: 1657896223
title: "ag, TLDR Pages"
description: "ag, The Silver Searcher. Comme ack, mais inspire à être plus rapide."
categories: "common"
---
> Plus d'informations : <https://github.com/ggreer/the_silver_searcher>.

- Trouve les fichiers qui contiennent "foo", et affiche les lignes correspondantes dans le contexte courant :

```bash
ag foo
```

- Trouve les fichiers qui contiennent "foo" dans un dossier spécifique :

```bash
ag foo chelin/vers/dossier
```

- Trouve les fichiers qui contiennent "foo", mais affiche les nom de fichier uniquement :

```bash
ag -l foo
```

- Trouve les fichiers qui contiennent "FOO" en étant insensible à la casse et affiche que le premier résultat plutôt que la ligne entière :

```bash
ag -i -o FOO
```

- Trouve "foo" dans les fichiers avec un nom contenant "bar" :

```bash
ag foo -G bar
```

- Trouve des fichiers dont le contenu correspond à une expression régulière :

```bash
ag '^ba(r|z)$'
```

- Trouve les fichiers avec un nom contenant "foo" :

```bash
ag -g foo
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | adguardhome, adscript, ag: add French translation (#8197) | 2022-07-15T16:43:43 | [69d02dd1e288](https://github.com/tldr-pages/tldr/commit/69d02dd1e28808ed632a954eb2d81469518626f2)

