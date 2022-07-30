---
author: ['Nicolas Hansse']
date: 1643284545
title: "7zr"
description: "7zr, Un archiveur de fichiers avec un haut taux de compression."
categories: "common"
---
> Similaire à `7z` sauf qu'il supporte que les fichiers `.7z`.

> Plus d'informations : <https://www.7-zip.org>.

- Compresse un fichier ou un dossier :

```bash
7zr a chemin/vers/archive.7z chemin/vers/le/fichier_ou_dossier
```

- Chiffre une archive existante (en incluant les en-têtes) :

```bash
7zr a chemin/vers/archive_chiffree.7z -ppassword -mhe=on chemin/vers/archive.7z
```

- Extrait une archive en conservant l'arborescence des fichiers :

```bash
7zr x chemin/vers/archive.7z
```

- Extrait une archive vers un dossier specifique :

```bash
7zr x chemin/vers/archive.7z -ochemin/vers/la/sortie
```

- Extrait une archive vers sortie standard :

```bash
7zr x chemin/vers/archive.7z -so
```

- Liste le contenu d'une archive :

```bash
7zr l chemin/vers/archive.7z
```

- Liste les types de compression disponible :

```bash
7zr i
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | 7za, 7zr: add French translation (#7712) | 2022-01-27T12:55:45 | [e667f1d51ee5](https://github.com/tldr-pages/tldr/commit/e667f1d51ee527d5a7940d2a2f3c8073cd1091d7)

