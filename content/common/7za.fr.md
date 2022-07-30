---
author: ['Nicolas Hansse']
date: 1643284545
title: "7za"
description: "7za, Un archiveur de fichiers avec un haut taux de compression."
categories: "common"
---
> Similaire à `7z` sauf qu'il supporte moins de type de fichiers mais il est multi-plateforme.

> Plus d'informations : <https://www.7-zip.org>.

- Compresse un fichier ou un dossier :

```bash
7za a chemin/vers/archive.7z chemin/vers/file_or_directory
```

- Chiffre une archive existante (en incluant les en-têtes) :

```bash
7za a chemin/vers/archive_chiffree.7z -pmotdepasse -mhe=on chemin/vers/archive.7z
```

- Extrait une archive en conservant l'arborescence des fichiers :

```bash
7za x chemin/vers/archive.7z
```

- Extrait une archive vers un dossier specifique :

```bash
7za x chemin/vers/archive.7z -ochemin/vers/la/sortie
```

- Extrait une archive vers sortie standard :

```bash
7za x chemin/vers/archive.7z -so
```

- Compresse en utilisant une compression spécifique :

```bash
7za a -t7z|bzip2|gzip|lzip|tar|zip chemin/vers/archive.7z chemin/vers/le/fichier_ou_dossier
```

- Liste le contenu d'une archive :

```bash
7za l chemin/vers/archive.7z
```

- Liste les types de compression disponible :

```bash
7za i
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | 7za, 7zr: add French translation (#7712) | 2022-01-27T12:55:45 | [e667f1d51ee5](https://github.com/tldr-pages/tldr/commit/e667f1d51ee527d5a7940d2a2f3c8073cd1091d7)

