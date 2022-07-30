---
author: ['Nicolas Hansse']
date: 1659170949
title: "asar"
description: "asar, Un outil d'archivage pour la plateforme Electron."
categories: "common"
---
> Plus d'informations : <https://github.com/electron/asar>.

- Archive un fichier ou un dossier :

```bash
asar pack chemin/vers/fichier_ou_dossier archive.asar
```

- Extrais une archive :

```bash
asar extract archive.asar
```

- Extrais un fichier spécifique d'une archive :

```bash
asar extract-file archive.asar fichier
```

- Liste les éléments contenus dans une archive :

```bash
asar list archive.asar
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | arping, asar: add French translation (#8263) | 2022-07-30T10:49:09 | [a443185d894a](https://github.com/tldr-pages/tldr/commit/a443185d894a61d8354b592125dcf14b83c05da1)

