---
author: ['qontinuum-dev']
date: 1634750727
title: "find, TLDR Pages"
description: "find, Trouve récursivement des fichiers ou des dossiers dans l'arborescence spécifiée."
categories: "common"
---
> Plus d'informations : <https://manned.org/find>.

- Trouve des fichiers par extension :

```bash
find racine -name '*.ext'
```

- Trouve des fichiers correspondant à plusieurs chemins ou motifs :

```bash
find racine -path '**/chemin/**/*.ext' -or -name '*motif*'
```

- Trouve des dossiers correspondant à un nom donné sans vérifier la casse :

```bash
find racine -type d -iname '*lib*'
```

- Trouve des fichiers correspondant à un motif donné en excluant certains chemins de la recherche :

```bash
find racine -name '*.py' -not -path '*/site-packages/*'
```

- Trouve des fichiers dans une fourchette de tailles :

```bash
find racine -size +500k -size -10M
```

- Exécute une commande pour chaque fichier (utiliser `{}` dans la commande pour utiliser le nom des fichiers) :

```bash
find racine -name '*.ext' -exec wc -l {} \;
```

- Trouve les fichiers modifiés dans les 7 derniers jours et les supprimer :

```bash
find racine -daystart -mtime -7 -delete
```

- Trouve les fichiers vides (de taille nulle) et les supprimer :

```bash
find racine -type f -empty -delete
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[qontinuum-dev](mailto:79641156+qontinuum-dev@users.noreply.github.com) | find: add French translation (#7059) | 2021-10-20T19:25:27 | [4ea95b2892d0](https://github.com/tldr-pages/tldr/commit/4ea95b2892d0993daed579386b78e7e3c71c52e0)

