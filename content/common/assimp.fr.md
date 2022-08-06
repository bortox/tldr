---
author: ['Nicolas Hansse']
date: 1659683614
title: "assimp"
description: "assimp, Client en ligne de commande pour l'Open Asset Import Library."
categories: "common"
---
> Supporte le chargement de plus de 40 formats de fichiers 3D, et exporte vers quelques formats 3D populaire.

> Plus d'informations : <http://www.assimp.org/>.

- Liste tous les formats d'import supportés :

```bash
assimp listext
```

- Liste tous les formats de sortie supportés :

```bash
assimp listexport
```

- Convertis un fichier vers un format de sortie supporté, avec les paramètres par défaut :

```bash
assimp export fichier_d_entrée.stl fichier_de_sortie.obj
```

- Convertis un fichier avec des paramètres personnalisés (le fichier dox_cmd.h dans le code source de assimp liste tous les paramètres disponible) :

```bash
assimp export fichier_d_entrée.stl fichier_de_sortie.obj paramètres
```

- Affiche un sommaire du contenu d'un fichier 3D :

```bash
assimp info chemin/vers/fichier
```

- Liste toutes les sous-commandes supportées ("mots") :

```bash
assimp help
```

- Affiche l'aide d'un sous-commande (e.g les paramètres qui lui sont spécifique) :

```bash
assimp sous_commande --help
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | assimp, astronomer: add French translation (#8285) | 2022-08-05T09:13:34 | [aefb4ec4e3e4](https://github.com/tldr-pages/tldr/commit/aefb4ec4e3e4d830688c5cee07eede2a490fd781)

