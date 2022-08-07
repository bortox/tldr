---
author: ['Nicolas Hansse']
date: 1659802506
title: "apg"
description: "apg, Crée arbitrairement les mots de passe aléatoires et complexes."
categories: "common"
---
> Plus d'informations : <https://manned.org/apg>.

- Crée des mots de passe aléatoires (la longueur par défaut est 8) :

```bash
apg
```

- Crée un mot de passe avec au moins 1 symbole (S), 1 Nombre (N), 1 Majuscule (C), 1 Minuscule (L) :

```bash
apg -M SNCL
```

- Crée un mot de passe avec 16 caractères :

```bash
apg -m 16
```

- Crée un mot de passe avec une longeur maximum de 16 :

```bash
apg -x 16
```

- Crée un mot de passe qui n'apparaît pas dans le dictionnaire (le fichier de dictionnaire doit être donné) :

```bash
apg -r fichier_dictionnaire
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | antibody, apg: add French translation (#8225) | 2022-08-06T18:15:06 | [cb0fe4c2c98f](https://github.com/tldr-pages/tldr/commit/cb0fe4c2c98f414a65d5b18a39efec14d236c3e8)

