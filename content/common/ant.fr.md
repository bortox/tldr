---
author: ['Nicolas Hansse']
date: 1658330478
title: "ant, TLDR Pages"
description: "ant, Apache Ant."
categories: "common"
---
> Outil pour construire et gérer les projets basés sur du Java.

> Plus d'informations : <https://ant.apache.org>.

- Construit un projet avec le fichier de construction `build.xml` :

```bash
ant
```

- Construit un projet en utilisant un autre fichier que `build.xml` :

```bash
ant -f fichier_de_construction.xml
```

- Affiche les informations sur les cibles possibles pour ce projet :

```bash
ant -p
```

- Affiche les informations de débogage :

```bash
ant -d
```

- Exécute toutes les cibles qui ne dépendent pas d'une ou plusieurs cibles en erreur :

```bash
ant -k
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansiweather, ant: add French translation (#8223) * ansiweather, ant: add French translation * chore: code review | 2022-07-20T17:21:18 | [a7e8269783f6](https://github.com/tldr-pages/tldr/commit/a7e8269783f6034ad59e413de1f6a2187fa896c5)

