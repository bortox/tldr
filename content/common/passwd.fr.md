---
author: ['Mia Combeau']
date: 1662480514
title: "passwd"
description: "passwd, Passwd est un outil de changement de mot de passe utilisateur."
categories: "common"
---
> Plus d'informations : <https://manned.org/passwd>.

- Change le mot de passe de l'utilisateur actuel :

```bash
passwd
```

- Change le mot de passe d'un utilisateur particulier :

```bash
passwd utilisateur
```

- Affiche l'état actuel du compte utilisateur :

```bash
passwd -S
```

- Supprime le mot de passe de l'utilisateur (supprime l'authentification par mot de passe pour l'utilisateur indiqué) :

```bash
passwd -d
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Mia Combeau](mailto:52008667+mcombeau@users.noreply.github.com) | passwd: add French translation (#8463) | 2022-09-06T18:08:34 | [cf4c29d35d78](https://github.com/tldr-pages/tldr/commit/cf4c29d35d78b7c7df55376b5732ff8f26ab499b)

