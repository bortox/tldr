---
author: ['Alexandre ZANNI']
date: 1633292868
title: "tr"
description: "tr, Convertisseur de caractères : exécute des remplacements basés sur des caractères uniques et des jeux de caractères."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/tr>.

- Remplace toutes les occurrences d'un caractère dans un fichier, et affiche le résultat :

```bash
tr caractère_recherché caractère_remplacé < fichier
```

- Remplace toutes les occurrences d'un caractère dans la sortie d'une autre commande :

```bash
echo texte | tr caractère_recherché caractère_remplacé
```

- Fais correspondre chaque caractère du premier ensemble au caractère correspondant du second ensemble :

```bash
tr 'abcd' 'jkmn' < fichier
```

- Supprime toutes les occurrences de l'ensemble de caractères spécifié dans l'entrée :

```bash
tr -d 'caractères_en_entrée' < fichier
```

- Comprime une série de caractères identiques en un seul caractère :

```bash
tr -s 'caractères_en_entrée' < fichier
```

- Traduis le contenu d'un fichier en majuscules :

```bash
tr "[:lower:]" "[:upper:]" < fichier
```

- Supprime les caractères non imprimables d'un fichier :

```bash
tr -cd "[:print:]" < fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Alexandre ZANNI](mailto:16578570+noraj@users.noreply.github.com) | tr: add French translation (#6673) | 2021-10-03T22:27:48 | [67f528101926](https://github.com/tldr-pages/tldr/commit/67f528101926db269c1bbe1b8c58a492ba211d03)

