---
author: ['Nicolas Hansse']
date: 1647646168
title: "ack"
description: "ack, Un outil de recherche comme grep, optimisé pour les développeurs."
categories: "common"
---
> Regardez aussi : `rg`, qui est beaucoup plus rapide.

> Plus d'informations : <https://beyondgrep.com/documentation>.

- Recherche des fichiers contenant une chaine de caractère ou une expression régulière dans le répertoire courant récursivement :

```bash
ack "motif_de_recherche"
```

- Recherche pour un motif insensible à la casse :

```bash
ack --ignore-case "motif_de_recherche"
```

- Recherche les lignes qui correspondent à un motif, affiche uniquement les textes correspondants et pas le reste de la ligne :

```bash
ack -o "motif_de_recherche"
```

- Limite la recherche aux fichiers d'un certain type :

```bash
ack --type=ruby "motif_de_recherche"
```

- Exlcus un certain type de fichier de la recherche :

```bash
ack --type=noruby "motif_de_recherche"
```

- Compte le nombre total de correspondances :

```bash
ack --count --no-filename "motif_de_recherche"
```

- Affiche les noms et le nombre total de correspondances pour chaque fichiers :

```bash
ack --count --files-with-matches "motif_de_recherche"
```

- Affiche toutes les valeurs qui peuvent être utilisées avec `--type` :

```bash
ack --help-types
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ack: add French Translation (#7867) | 2022-03-19T00:29:28 | [78d53b25f353](https://github.com/tldr-pages/tldr/commit/78d53b25f353ab80da3b5a48f0f8e55a4a799fcd)

