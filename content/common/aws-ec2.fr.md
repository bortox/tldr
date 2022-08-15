---
author: ['Nicolas Hansse']
date: 1660526854
title: "aws ec2"
description: "aws ec2, CLI pour AWS EC2."
categories: "common"
---
> Provisionne, sécurise et des capacités de calcul redimensionnable dans le cloud AWS pour accélérer le développement et le déploiement d'applications.

> Plus d'informations : <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ec2/index.html>.

- Affiche la liste de toutes les commandes EC2 disponible :

```bash
aws ec2 help
```

- Affiche l'aide pour une sous-commande EC2 spécifique :

```bash
aws ec2 sous-commande help
```

- Affiche les informations sur une instance spécifique :

```bash
aws ec2 describe-instances --instance-ids id_d_instance
```

- Affiche les informations de toutes les instances :

```bash
aws ec2 describe-instances
```

- Affiche les informations sur tous les volumes EC2 :

```bash
aws ec2 describe-volumes
```

- Supprime un volume EC2 :

```bash
aws ec2 delete-volume --volume-id id_de_volume
```

- Crée une sauvegarde de votre volume EC2 :

```bash
aws ec2 create-snapshot --volume-id id_de_volume
```

- Liste toutes les AMIs (Images de Machine Amazon) disponible :

```bash
aws ec2 describe-images
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-cur, aws-ec2, aws-ecr: add French translation (#8347) | 2022-08-15T03:27:34 | [bf5dda040436](https://github.com/tldr-pages/tldr/commit/bf5dda0404366824635ab6c4ef4f7572d7a2d334)

