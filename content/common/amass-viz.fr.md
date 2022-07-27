---
author: ['Nicolas Hansse']
date: 1658041505
title: "amass viz, TLDR Pages"
description: "amass viz, Visualise les informations recueillies dans graphique de réseau."
categories: "common"
---
> Plus d'informations : <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-viz-subcommand>.

- Génère une visualisation D3.js basé sur la data de la base de données :

```bash
amass viz -d3 -dir chemin/vers/la_base_de_données
```

- Génère un fichier DOT basé sur la data de la base de données :

```bash
amass viz -dot -dir chemin/vers/la_base_de_données
```

- Génère un fichier GEXF basé sur la data de la base de données :

```bash
amass viz -gexf -dir chemin/vers/la_base_de_données
```

- Génère un fichier JSON Graphistry basé sur la data de la base de données :

```bash
amass viz -graphistry -dir chemin/vers/la_base_de_données
```

- Génère un fichier CSV Maltego basé sur la data de la base de données :

```bash
amass viz -maltego -dir chemin/vers/la_base_de_données
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | amass-intel, amass-track, amass-viz: add French translation (#8210) | 2022-07-17T09:05:05 | [3ce8ac7de035](https://github.com/tldr-pages/tldr/commit/3ce8ac7de035f7f1be6e9285df49bbe28b35ad56)

