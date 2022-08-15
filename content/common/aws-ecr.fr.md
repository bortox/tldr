---
author: ['Nicolas Hansse']
date: 1660526854
title: "aws ecr"
description: "aws ecr, Pousse, récupère et gère les images de conteneur."
categories: "common"
---
> Plus d'informations : <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ecr/index.html>.

- Connecte docker avec le registre par défaut (le nom d'utilisateur est AWS) :

```bash
aws ecr get-login-password --region région | docker login --username AWS --password-stdin id_de_compte_aws.dkr.ecr.région.amazonaws.com
```

- Crée un dépôt :

```bash
aws ecr create-repository --repository-name dépôt --image-scanning-configuration scanOnPush=true|false --region région
```

- Tag une image locale pour ECR :

```bash
docker tag nom_de_conteneur:tag id_de_compte_aws.dkr.ecr.région.amazonaws.com/nom_de_conteneur:tag
```

- Pousse une image dans le dépôt :

```bash
docker push id_de_compte_aws.dkr.ecr.région.amazonaws.com/nom_de_conteneur:tag
```

- Récupère une image depuis un dépôt :

```bash
docker pull id_de_compte_aws.dkr.ecr.région.amazonaws.com/nom_de_conteneur:tag
```

- Supprime une image d'un dépôt :

```bash
aws ecr batch-delete-image --repository-name dépôt --image-ids imageTag=latest
```

- Supprime un dépôt :

```bash
aws ecr delete-repository --repository-name dépôt --force
```

- Liste les images dans un dépôt :

```bash
aws ecr list-images --repository-name dépôt
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-cur, aws-ec2, aws-ecr: add French translation (#8347) | 2022-08-15T03:27:34 | [bf5dda040436](https://github.com/tldr-pages/tldr/commit/bf5dda0404366824635ab6c4ef4f7572d7a2d334)

