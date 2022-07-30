---
author: ['Nicolas Hansse']
date: 1658041231
title: "amass enum"
description: "amass enum, Trouve les sous-domaines d'un domaine."
categories: "common"
---
> Plus d'informations : <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-enum-subcommand>.

- Trouve les sous-domaines d'un domaine passivement :

```bash
amass enum -passive -d nom_de_domaine
```

- Trouve les sous-domaines d'un domaine et les verifie activement en essayant de résoudre les sous-domaines trouvés :

```bash
amass enum -active -d nom_de_domaine -p 80,443,8080
```

- Fait recherche par force brute pour les sous-domaines :

```bash
amass enum -brute -d nom_de_domaine
```

- Sauvegarde les résultats vers un fichier texte :

```bash
amass enum -o fichier_de_sortie -d nom_de_domaine
```

- Sauvegarde les résultats dans une base de données :

```bash
amass enum -o fichier_de_sortie -dir chemin/vers/la_base_de_données
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | amass, amass-db, amass-enum: add French translation (#8209) | 2022-07-17T09:00:31 | [97d47723bb66](https://github.com/tldr-pages/tldr/commit/97d47723bb660e92b33cc0a187eb572fa328bba5)

