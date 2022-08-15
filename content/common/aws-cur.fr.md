---
author: ['Nicolas Hansse']
date: 1660526854
title: "aws cur"
description: "aws cur, Crée, requête et supprime des rapports de définition d'utilisation AWS."
categories: "common"
---
> Plus d'informations : <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/cur/index.html>.

- Créé un rapport de définition de coût et d'utilisation AWS depuis un fichier JSON :

```bash
aws cur put-report-definition --report-definition file://chemin/vers/rapport_de_définition.json
```

- Liste les rapports de définition définis pour le compte connecté :

```bash
aws cur describe-report-definitions
```

- Supprime un rapport de définition d'utilisation :

```bash
aws cur --region region_aws delete-report-definition --report-name rapport
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-cur, aws-ec2, aws-ecr: add French translation (#8347) | 2022-08-15T03:27:34 | [bf5dda040436](https://github.com/tldr-pages/tldr/commit/bf5dda0404366824635ab6c4ef4f7572d7a2d334)

