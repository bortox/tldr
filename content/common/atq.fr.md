---
author: ['Nicolas Hansse']
date: 1659879985
title: "atq"
description: "atq, Affiche les travaux programmés par la commande `at` ou `batch`."
categories: "common"
---
> Plus d'informations : <https://manned.org/atq>.

- Affiche les travaux programmés de l'utilisateur courant :

```bash
atq
```

- Affiche les travaux de la file nommé 'a' (les files ont des noms avec une seule lettre) :

```bash
atq -q a
```

- Affiche les travaux de tous les utilisateurs (lancé en tant que super-utilisateur) :

```bash
sudo atq
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | atq, atrm, auditd: add French translation (#8316) | 2022-08-07T15:46:25 | [a5b3b4ad5ce4](https://github.com/tldr-pages/tldr/commit/a5b3b4ad5ce4b5fce6b843cc934852f11dfcc75d)

