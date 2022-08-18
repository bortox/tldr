---
author: ['Nicolas Hansse']
date: 1660736158
title: "aws-google-auth"
description: "aws-google-auth, Outil en ligne de commande pour obtenir des credentials AWS temporaire (STS) en utilisant Google Apps comme un fournisseur de fédération (SSO)."
categories: "common"
---
> Plus d'informations : <https://github.com/cevoaustralia/aws-google-auth>.

- Connecte l'utilisateur avec le SSO Google en utilisant les identifiants IDP et SP et donne une durée de vie d'une heure à la connection :

```bash
aws-google-auth -u exemple@exemple.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600
```

- Connecte l'utilisateur en lui demandant quel rôle utiliser (dans le cas où il y a plusieurs rôles SAML) :

```bash
aws-google-auth -u exemple@exemple.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600 -a
```

- Résous les alias pour des comptes AWS :

```bash
aws-google-auth -u exemple@exemple.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600 -a --resolve-aliases
```

- Affiche l'aide :

```bash
aws-google-auth -h
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | aws-glue, aws-google-auth: add French translation (#8361) | 2022-08-17T13:35:58 | [518a2fe777b6](https://github.com/tldr-pages/tldr/commit/518a2fe777b691732cac3ea36e3edf27ecda5295)

