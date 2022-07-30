---
author: ['Gatien']
date: 1646593072
title: "abbr"
description: "abbr, Gère les abréviations pour le shell Fish."
categories: "linux"
---
> Les mots définis par l'utilisateur sont remplacés par des phrases plus longues après leur saisie.

> Plus d'informations : <https://fishshell.com/docs/current/cmds/abbr.html>.

- Ajoute une nouvelle abréviation :

```bash
abbr --add nom_abrégé commande arguments_de_la_commande
```

- Renomme une abréviation existante :

```bash
abbr --rename ancien_nom nouveau_nom
```

- Supprime une abréviation existante :

```bash
abbr --erase nom_abrégé
```

- Importe les abréviations définies sur un autre hôte via SSH :

```bash
ssh nom_de_l_hôte abbr --show | source
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Gatien](mailto:Gatien.vilain@student.junia.com) | abbr: add French translation (#7854) | 2022-03-06T19:57:52 | [6c177bf48b13](https://github.com/tldr-pages/tldr/commit/6c177bf48b134c4d03e02af12cb57827e8602e04)

