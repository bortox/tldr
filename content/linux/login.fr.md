---
author: ['Copolycube']
date: 1635196527
title: "login"
description: "login, Démarre une session pour un utilisateur"
categories: "linux"
---
> Plus d'informations : <https://manned.org/login>.

- Démarrer une session en tant qu'utilisateur :

```bash
login utilisateur
```

- Démarrer une session en tant qu'utilisateur sans authentification si jamais l'utilisateur est déjà pré-authentifié :

```bash
login -f utilisateur
```

- Démarrer une session en tant qu'utilisateur et en préservant l'environnement courant :

```bash
login -p utilisateur
```

- Démarrer une session en tant qu'utilisateur sur un hôte distant :

```bash
login -h hote utilisateur
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Copolycube](mailto:kaourintin+github@gmail.com) | login: add French translation (#7002) | 2021-10-25T23:15:27 | [3166ca68a509](https://github.com/tldr-pages/tldr/commit/3166ca68a509e1bacef42777ac51f4ad159e143a)

