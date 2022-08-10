---
author: ['Nicolas Hansse']
date: 1660027945
title: "autopep8"
description: "autopep8, Formate du code Python en accord avec le style PEP 8."
categories: "common"
---
> Plus d'informations : <https://github.com/hhatto/autopep8>.

- Formate une fichier vers la sortie standard, avec une taille de ligne maximal personnalisée :

```bash
autopep8 chemin/vers/fichier.py --max-line-length longueur
```

- Formate un fichier, en affichant les changements :

```bash
autopep8 --diff chemin/vers/fichier
```

- Formate un fichier et sauvegarde les changements :

```bash
autopep8 --in-place chemin/vers/fichier.py
```

- Formate récursivement les fichiers dans un dossier et sauvegarde les changements :

```bash
autopep8 --in-place --recursive chemin/vers/dossier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | autoflake, autojump, autopep8: add French translation (#8325) | 2022-08-09T08:52:25 | [4d73e2c45d11](https://github.com/tldr-pages/tldr/commit/4d73e2c45d113e6d6c60e0cce245a79f9d3830f3)

