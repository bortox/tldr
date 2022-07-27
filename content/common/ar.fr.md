---
author: ['Nicolas Hansse']
date: 1658610856
title: "ar, TLDR Pages"
description: "ar, Crée, modifie et extrais depuis des archives (`.a`, `.so`, `.o`)."
categories: "common"
---
> Plus d'informations : <https://manned.org/ar>.

- Extrais tous les éléments depuis une archive :

```bash
ar -x chemin/vers/archive.a
```

- Liste tous les éléments depuis une archive :

```bash
ar -t chemin/vers/archive.a
```

- Remplace ou ajoute des fichiers à une archive :

```bash
ar -r chemin/vers/archive.a chemin/vers/fichier1.o chemin/vers/fichier2.o
```

- Insère un fichier d'indexation (équivalent à `ranlib`) :

```bash
ar -s chemin/vers/archive.a
```

- Crée une archive avec des fichiers et un fichier d'indexation qui l'accompagne :

```bash
ar -rs chemin/vers/archive.a chemin/vers/fichier1.o chemin/vers/fichier2.o
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ar, arc, arch: add French translation (#8240) | 2022-07-23T23:14:16 | [09f51537dd05](https://github.com/tldr-pages/tldr/commit/09f51537dd05b40033d4e81c99f2f8131e2f0009)

