---
author: ['Nicolas Hansse']
date: 1660027945
title: "autoflake"
description: "autoflake, Un outil pour enlever les imports et les variables inutilisés d'un code Python."
categories: "common"
---
> Plus d'informations : <https://github.com/myint/autoflake>.

- Enlève les variables non-utilisées d'un fichier et affiche la différence :

```bash
autoflake --remove-unused-variables fichier.py
```

- Enlève les imports non-utilisés de plusieurs fichiers et affiche la différence :

```bash
autoflake --remove-all-unused-imports fichier1.py fichier2.py fichier3.py
```

- Enlève les variables non-utilisées d'un fichier, surcharge ce dernier :

```bash
autoflake --remove-unused-variables --in-place fichier.py
```

- Enlève les variables non-utilisées de tous les fichiers d'un dossier de manière récursive, en les surchargeant :

```bash
autoflake --remove-unused-variables --in-place --recursive chemin/vers/dossier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | autoflake, autojump, autopep8: add French translation (#8325) | 2022-08-09T08:52:25 | [4d73e2c45d11](https://github.com/tldr-pages/tldr/commit/4d73e2c45d113e6d6c60e0cce245a79f9d3830f3)

