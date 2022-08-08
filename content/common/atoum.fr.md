---
author: ['Nicolas Hansse']
date: 1659887262
title: "atoum"
description: "atoum, Un framework de test unitaire pour PHP simple, moderne et intuitif."
categories: "common"
---
> Plus d'informations : <http://atoum.org>.

- Initialise un fichier de configuration :

```bash
atoum --init
```

- Lance les tests :

```bash
atoum
```

- Lance les tests avec un fichier de configuration donné :

```bash
atoum -c chemin/vers/fichier
```

- Lance un fichier de test spécifique :

```bash
atoum -f chemin/vers/fichier
```

- Lance les tests présent dans dossier donné :

```bash
atoum -d chemin/vers/dossier
```

- Lance tous les tests sous un certain namespace :

```bash
atoum -ns namespace
```

- Lance tous les tests avec un certain tag :

```bash
atoum -t tag
```

- Charge un fichier d'amorce avant de lancer les tests :

```bash
atoum --bootstrap-file chemin/vers/fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | astyle, atoum: add French translation (#8305) | 2022-08-07T17:47:42 | [404e05cf822d](https://github.com/tldr-pages/tldr/commit/404e05cf822db5a9d7b8e96505dccc9e796c4851)

