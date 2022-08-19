---
author: ['Nicolas Hansse']
date: 1660872394
title: "aws iam"
description: "aws iam, CLI pour AWS IAM."
categories: "common"
---
> Plus d'informations : <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/iam/index.html>.

- Affiche la page d'aide pour `aws iam` (avec toutes les commandes iam disponibles) :

```bash
aws iam help
```

- Liste les utilisateurs :

```bash
aws iam list-users
```

- Liste les politiques :

```bash
aws iam list-policies
```

- Liste les groupes :

```bash
aws iam list-groups
```

- Récupère les utilisateurs dans un groupe :

```bash
aws iam get-group --group-name nom_du_groupe
```

- Décris une politique IAM :

```bash
aws iam get-policy --policy-arn arn:aws:iam::aws:policy/nom_de_la_politique
```

- Liste les clés d’accès :

```bash
aws iam list-access-keys
```

- Liste les clés d'accès pour un utilisateur spécifique :

```bash
aws iam list-access-keys --user-name nom_d_utilisateur
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-help, aws-iam: add French translation (#8369) | 2022-08-19T03:26:34 | [3b4bf8b26019](https://github.com/tldr-pages/tldr/commit/3b4bf8b26019571ce5b727b49511fc80b41292b3)

