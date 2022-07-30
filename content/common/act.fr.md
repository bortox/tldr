---
author: ['Nicolas Hansse']
date: 1657536162
title: "act"
description: "act, Execute des GitHub Actions en local avec Docker."
categories: "common"
---
> Plus d'informations : <https://github.com/nektos/act>.

- Liste les actions disponibles :

```bash
act -l
```

- Execute l'événement par défault :

```bash
act
```

- Execute un événement spécifique :

```bash
act type_d_événement
```

- Execute une action spécifique :

```bash
act -a id_action
```

- Ne pas lancer les actions maintenant (e.g un essai) :

```bash
act -n
```

- Affiche le journal en mode verbeux :

```bash
act -v
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | act: add French translation (#8192) | 2022-07-11T12:42:42 | [b0c4ede3e97f](https://github.com/tldr-pages/tldr/commit/b0c4ede3e97f693523bab8b9b3d05541284c39ba)

